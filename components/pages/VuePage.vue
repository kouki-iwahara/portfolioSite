<template>
  <div class="content container-fluid">
    <div class="row">
      <div class="content_title col-sm-12">
        <h2 :id="vueId">Vue.js</h2>
        <p>
          Vue.jsの学習は、フレームワークの理解をより深める為に、純正のJavaScriptで実装した内容と同じものを作りました。
        </p>
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
          <div class="col-sm-12 content_text">
            <h3>FizzBuzz</h3>
            <a
              href="https://github.com/kouki-iwahara/vue_FizzBuzz"
              target="”_blank”"
              >GitHubソースコード</a
            >
            <p>【学んだこと】</p>
            <p>・v-modelを使用したレンダリング</p>
            <p>
              ブラウザに入力した文字をv-modelを使用し取得する方法を学びました。<br />
              また、書籍で主要なオプションやコンポーネントの使用方法を学びました。
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/ab1bcf6e948e37fbdd8b"
                target="”_blank”"
                >Qiita執筆:主要なオプションオブジェクトのまとめ
              </a>
            </p>
            <div>
              <p>学んだ書籍</p>
              <p>・動かして学ぶ！Vue.js開発入門</p>
              <img
                class="img-fluid img-thumbnail mh-100 d-block book-img"
                src="../../assets/image/vue-develop.jpg"
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
          <div class="col-sm-12 content_text">
            <h3>簡易ToDoリスト</h3>
            <p>
              <a
                href="https://github.com/kouki-iwahara/vue_TodoList"
                target="”_blank”"
                >GitHubソースコード</a
              >
            </p>
            <p>
              <a
                href="https://github.com/kouki-iwahara/vuex_todoList"
                target="”_blank”"
                >Vuexを使用 GitHubソースコード</a
              >
            </p>

            <p>【学んだこと】</p>
            <p>
              Vuexとgit-flow使用して開発し、チームでの開発を意識しました。
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/11ebb08863c38bd0c8fd"
                target="”_blank”"
                >Qiita執筆:
                v-forを使う時、配列に初期値があると初めから画面に表示されてしまう
              </a>
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/f1cc04559a81a728785a"
                target="”_blank”"
                >Qiita執筆:コンポーネントの基本的な説明と書き方
              </a>
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/ff5748db977768fd7669"
                target="”_blank”"
                >Qiita執筆:Vuexの入り口
              </a>
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/1a75daaa93657b0b56d7"
                target="”_blank”"
                >Qiita執筆:ストアの4つの概念まとめ
              </a>
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/a00b4bfd4a649e1062e3"
                target="”_blank”"
                >Qiita執筆:テンプレートがコンパイルできない
              </a>
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/839f924bc4460c55cbf0"
                target="”_blank”"
                >Qiita執筆:ストアとコンポーネント間の通信
              </a>
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/e80d6ec66cdd25ff7bab"
                target="”_blank”"
                >Qiita執筆:単一ファイルコンポーネント〜機能解説からビルド〜
              </a>
            </p>
            <p>
              <a
                href="https://qiita.com/kouki-iwahara/items/5941ed7b7edf5dc41a54"
                target="”_blank”"
                >Qiita執筆:Vuex、Vue-router、コンポーネントの基礎がまとめて分かる簡易カウンターアプリを作る
              </a>
            </p>
            <div>
              <p>【学んだ書籍】</p>
              <p>・Vue.js入門 基礎から実践アプリケーション開発まで</p>
              <img
                class="img-fluid img-thumbnail mh-100 d-block book-img"
                src="../../assets/image/vue-app.jpg"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
      <div class="content_title col-sm-12">
        <h2 :id="nuxtId">Nuxt.js</h2>
        <p>
          Vue.jsのフレームワークであるNuxt.jsを書籍で学びました。
        </p>
      </div>
      <div class="col-sm-4 content_book">
        <p>・Vue.js入門 基礎から実践アプリケーション開発まで</p>
        <img
          class="img-fluid img-thumbnail mh-100 mx-auto d-block book-img"
          src="../../assets/image/Nuxt.jpg"
          alt=""
        />
      </div>
      <div class="col-sm-6">
        <p>【Nuxtを使用した理由】</p>
        <p>
          ・ディレクトリ構成やルーティング・レンダリングなどを行ってくれる。
        </p>
        <p>
          ・ページ毎の機能が決まっているのでVue.jsに比べると、良い意味で規則が堅い
        </p>
        <p>
          ・知的好奇心が強くモダンなフレームワークに触れたかった
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    vueId: {
      type: String,
      default: null
    },
    nuxtId: {
      type: String,
      default: null
    }
  }
}
</script>

<style scoped>
.content_title {
  text-align: center;
}

.content_image {
  margin: 0 0 40px auto;
  height: 450px;
}

.content_text {
  margin-bottom: 40px;
}

.content_book {
  margin: 0 0 40px auto;
}

.book-img {
  height: 150px;
}
</style>
