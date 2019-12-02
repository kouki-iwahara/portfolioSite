<template>
  <div class="content container-fluid">
    <div class="row">
      <div class="content_title col-sm-12">
        <h2 :id="id">JavaScript</h2>
      </div>
      <div class="col-sm-4 content_image">
        <video
          loop
          autoplay
          muted
          class="img-fluid img-thumbnail mh-100 mx-auto d-block"
          src="../../assets/image/fizzbuzz.mp4"
        />
      </div>
      <div class="col-sm-6">
        <div class="row">
          <div class="col-sm-12 content_profile">
            <h3 class="col-sm-12">FizzBuzz</h3>
            <a
              href="https://github.com/kouki-iwahara/javascript_practice1"
              target="”_blank”"
              >GitHubソースコード</a
            >
            <p>【学んだこと】</p>
            <p>・DOM</p>
            <p>
              ブラウザに入力した文字を取得し、操作して反映させる仕組みを学びました。
            </p>
            <p>・if文の条件分岐</p>
            <p>
              if文の条件分岐の実行順番やNaNを使った条件分岐の方法に注意が必要だと学びました。
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/8e1e16fb836fbb7a6859"
                target="”_blank”"
                >Qiita執筆: NaNを使った条件分岐について</a
              >
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/a85b4c9260ef545b7a52"
                target="”_blank”"
                >Qiita執筆: データ型を文字列として取得する際の書き方と注意点</a
              >
            </p>
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
            <a
              href="https://github.com/kouki-iwahara/javascript_practice2"
              target="”_blank”"
              >GitHubソースコード</a
            >
            <p>【学んだこと】</p>
            <p>・オブジェクト指向</p>
            <p>
              オブジェクトを生成し、todoのデータを個別に保持する方法を学びました
            </p>
            <p>
              ・データの登録、表示、更新、削除をフロント側で実装
            </p>
            <p>
              任意のタスクの更新や削除の実装に悩まされました。<br />
              自力で調べたり、メンターさんに質問する等して実装できました。<br />
              また、コードレビューしてもらう際の可読性向上の為に、読みやすいコードを書くという意識をしました。
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/3c31fdfc74ac0b8a5137"
                target="”_blank”"
                >Qiita執筆: オブジェクトを生成し情報を保持する</a
              >
            </p>
          </div>
        </div>
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
            <a href="https://github.com/kouki-iwahara/QuizApp" target="”_blank”"
              >GitHubソースコード</a
            >
            <p>【学んだこと】</p>
            <p>・外部APIの取得</p>
            <p>
              fetchメソッドを使用した外部APIの取得方法を学びました。
            </p>
            <p>
              ・非同期処理
            </p>
            <p>
              thenメソッドを使用した非同期処理を学びました。
            </p>
            <p>【ポイント】</p>
            <p>実装を適切に関数に分け、可読性を意識しました。</p>
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
</style>
