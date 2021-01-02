<template>
    <div id="home">
        <h1>エディター画面</h1>
        <!-- <p>
            <span>{{ user.displayName }}</span>
            <button @click="logout">ログアウト</button>
        </p> -->
        <div>
            メモリスト
            <div v-for="(memo, index) in memoList" :key="index">
                <div v-if="index!=0" v-html="displayMemo(memo.markdown)"></div>
            </div>
            <textarea class="markdown" v-model="memoList[memoIndex].markdown"></textarea>
            <div><button v-on:click="addMemo">メッセージ追加</button></div><br>
            プレビュー<div v-html="preview()"></div>
        </div>
    </div>
</template>
<script>
import marked from "marked";
export default {
    name: 'editor',
    props: ["user"],
    data() {
        return {
            memoList: [
                {
                    markdown: "",
                }
            ],
            memoIndex: 0
        };
    },
    methods: {
        // // ログアウト機能
        // logout: function() {
        //     firebase.auth().signOut();
        // },
        // markdown書式でのプレビュー表示
        preview: function() {
            return marked(this.memoList[this.memoIndex].markdown);
        },
        // メモを追加
        addMemo: function() {
            this.memoList.push({
                markdown: marked(this.memoList[this.memoIndex].markdown)
            });
        },
        // 作成したメモを一覧表示
        displayMemo: function(text) {
            return text.split(/\n/)[0];
        }
    }
}
</script>