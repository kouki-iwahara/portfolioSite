<template>
  <div class="content container-fluid">
    <div class="row">
      <div class="content_title col-sm-12">
        <h2 :id="id">Node.js</h2>
        <p>
          Node.jsの学習は、書籍でNode.jsを学習してから、純正のJavaScriptで制作したクイズアプリ、ToDoリストをExpress.jsを使用してMVCの概念に基づき実装しました。
        </p>
      </div>

      <div class="col-sm-4 content_image-quiz">
        <video
          loop
          autoplay
          muted
          class="img-fluid img-thumbnail mh-100 mx-auto d-block"
          src="../../assets/image/quiz.mp4"
        />
      </div>
      <div class="col-sm-6">
        <div class="row">
          <div class="col-sm-12 content_profile">
            <h3>クイズアプリ</h3>
            <a
              href="https://github.com/kouki-iwahara/QuizApp_MVC"
              target="”_blank”"
              >GitHubソースコード</a
            >
            <p>【学んだこと】</p>
            <p>
              ・外部APIをバックエンドで取得しデータを生成、フロントへのデータの渡し方
            </p>
            <p>
              クイズの問題を一問毎にバックエンドへアクセスするのではなく、初回のみアクセスするようにしました。
            </p>
            <p>
              ・MVCの概念
            </p>
            <p>
              MVCの概念に基づき、役割事にページを分割して実装しました。
            </p>
            <div>
              <p>【学んだ書籍】</p>
              <p>・Node.js超入門[第2版]</p>
              <img
                class="img-fluid img-thumbnail mh-100 d-block book-img"
                src="../../assets/image/node.jpg"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>

      <div class="col-sm-4 content_image">
        <video
          loop
          autoplay
          muted
          class="img-fluid img-thumbnail mh-100 mx-auto d-block"
          src="../../assets/image/todo.mp4"
        />
      </div>
      <div class="col-sm-6">
        <div class="row">
          <div class="col-sm-12 content_profile">
            <h3>簡易ToDoリスト</h3>
            <a href="https://github.com/kouki-iwahara/todoApp" target="”_blank”"
              >GitHubソースコード</a
            >
            <p>【学んだこと】</p>
            <p>・Nuxt+Express+MySQLでデータベースのCRUD</p>
            <p>
              axiosを使ってNodeにアクセスし、データベースのCRUDを学び、一通りの操作をできるようにしました。<br />
              また、テストしやすいように関数をstoreに寄せて記述しました。
            </p>
            <p>
              ・Jestでテストコード記述
            </p>
            <p>
              フロントのテストコードを簡単にですが記述し、テスト駆動開発の大切さを学びました。
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/2666554298f139af3433"
                target="”_blank”"
                >Qiita執筆:
                @nuxt/axiosでCRUDする時のアクセス方法とデータの受け取り方</a
              >
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/fdf13432db05841d0e4f"
                target="”_blank”"
                >Qiita執筆: Nuxt + Node(Express) +
                passportでsession認証機能の実装まとめ</a
              >
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    id: {
      type: String,
      default: null
    }
  }
}
</script>

<style scoped>
.content {
  background-color: #f4f5f7;
}

.content_title {
  text-align: center;
}

.content_image {
  margin: 0 0 40px auto;
  height: 450px;
}

.content_image-quiz {
  margin: 0 0 40px auto;
}

.book-img {
  height: 150px;
  margin-bottom: 40px;
}
</style>
