<template>
  <div class="content container-fluid">
    <div class="row">
      <div class="content_title col-sm-12">
        <h2 :id="id">Others</h2>
      </div>
      <div class="content_title col-sm-12">
        <h3>もくもく会主催</h3>
      </div>
      <div class="col-sm-6 content_text">
        <div class="row">
          <div class="col-sm-12 content_profile">
            <h3>初参加で初主催</h3>
            <p>
              地元の新潟では参加・開催が難しかったもくもく会を、12月に東京に引っ越した事で、同月21日（土）に主催する事にしました。
            </p>
            <p>【もくもく会内容（予定）】</p>
            <ul>
              <li>所属しているメンターさんのコミュニティーのメンバー4〜6人</li>
              <li>15分簡単な自己紹介、3時間半学習、15分成果発表・意見交換</li>
            </ul>
            <p>
              <span
                >やると決めたら即行動し、企画力、コミュニケーション力があります。</span
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

.content_text {
  margin: 0 auto 40px;
}

span {
  color: red;
}
</style>
