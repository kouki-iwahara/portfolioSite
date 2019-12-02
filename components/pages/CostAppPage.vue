<template>
  <div class="content container-fluid">
    <div class="row">
      <div class="content_title col-sm-12">
        <h2 :id="id">個人開発</h2>
        <h3>飲食店の業務改善、レシピの共有がテーマ</h3>
        <p>
          これまでのスキルを総動員して、実際の現場でも使える飲食店の業務改善・レシピの共有をテーマにしたwebアプリを作成。<br />
          まだ改善の余地が多くあるので、グロースしていきます。
        </p>
      </div>

      <div class="col-sm-4 content_image-quiz">
        <video
          controls
          muted
          class="img-fluid img-thumbnail mh-100 mx-auto d-block"
          src="../../assets/image/todo.mp4"
        />
      </div>
      <div class="col-sm-6 content_text">
        <div class="row">
          <div class="col-sm-12 content_profile">
            <h3>原価管理アプリ</h3>
            <a href="https://github.com/kouki-iwahara/CostApp"
              >GitHubソースコード</a
            >
            <p>内容</p>
            <p>
              自身の飲食業界の業務経験から、あったら便利だなと思ったものを作成。<br />
              食材とレシピのデータを登録し、原価や利益を簡単に管理できる。<br />
              レシピに使われている食材や、食材が使用されているレシピも表示される。<br />
              登録されたレシピは共有され、新しいレシピを作成する際の情報源となる。
            </p>
            <p>作成のポイント</p>
            <ul>
              <li>
                レシピに登録された食材のデータを中間テーブルとして作成し、食材テーブルとレシピテーブルの両方に紐付けた
              </li>
              <li>SPA構築でUX向上を意識</li>
              <li>
                検索結果を入力された文字とレンダリングして、リアルタイムに検索結果を表示
              </li>
              <li>開発にDockerを使用</li>
              <li>テストにCircleCIを使用</li>
              <li>コンポーネントの設計を、現在AtomicDesignに基づき修正中</li>
            </ul>
            <p>
              <span
                >日頃の業務から問題点を見つけ出し、改善策を考え、行動に移す力があります。</span
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

.content_text {
  margin-bottom: 40px;
}

.book-img {
  height: 150px;
  margin-bottom: 40px;
}

span {
  color: red;
}
</style>
