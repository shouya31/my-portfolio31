<template>
  <section class="section">
    <div class="container" id="app">
      <p class="title is-1 has-text-centered has-text-white" style="font-family: cursive;">SKILL</p>
      <div class="columns" v-scroll="handleScroll">
        <div class="card column">
          <div class="skill-desc">
            <h3 class="title skill-desc-title">
              <i class="fas fa-desktop"></i>デザイン・コーディング
            </h3>
            <p></p>
            <table class="table is-fullwidth table-borderless">
              <thead>
                <tr>
                  <th scope="col">技術</th>
                  <th scope="col">経験年数</th>
                  <th scope="col">スキル</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <th scope="row">HTML5</th>
                  <td>１年</td>
                  <td>
                    <span class="rating">
                      <p class="rate rate4"></p>
                    </span>
                  </td>
                </tr>
                <tr>
                  <th scope="row">CSS3</th>
                  <td>１年</td>
                  <td>
                    <p>Bulma</p>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>

        <div class="card column">
          <div class="skill-desc">
            <h3 class="title skill-desc-title">
              <i class="fas fa-desktop"></i>フロントエンド
            </h3>
            <p></p>
            <table class="table is-fullwidth table-borderless">
              <thead>
                <tr>
                  <th scope="col">技術</th>
                  <th scope="col">経験年数</th>
                  <th scope="col">スキル</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <th scope="row">jQuery</th>
                  <td>半年〜１年未満</td>
                  <td>
                    <p>Ajax通信</p>
                  </td>
                </tr>
                <tr>
                  <th scope="row">vue.js</th>
                  <td>半年〜１年未満</td>
                  <td>
                    <span class="rating">
                      <p class="rate rate4"></p>
                    </span>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>

      <div class="columns" v-scroll="handleScroll">
        <div class="card column">
          <div class="skill-desc">
            <h3 class="title skill-desc-title">
              <i class="fas fa-desktop"></i>バックエンド
            </h3>
            <p></p>
            <table class="table is-fullwidth table-borderless">
              <thead>
                <tr>
                  <th scope="col">技術</th>
                  <th scope="col">経験年数</th>
                  <th scope="col">スキル</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <th scope="row">Rails</th>
                  <td>約１年</td>
                  <td>
                    <p></p>
                  </td>
                </tr>
                <tr>
                  <th scope="row">Golang</th>
                  <td>半年未満</td>
                  <td>
                    <span class="rating">
                      <p class="rate rate4"></p>
                    </span>
                  </td>
                </tr>
                <tr>
                  <th scope="row">Nuxt.js</th>
                  <td>半年未満</td>
                  <td>
                    <span class="rating">
                      <p class="rate rate4"></p>
                    </span>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>

        <div class="card column">
          <div class="skill-desc">
            <h3 class="title skill-desc-title">
              <i class="fas fa-desktop"></i>その他のツール
            </h3>
            <p></p>
            <table class="table is-fullwidth table-borderless">
              <thead>
                <tr>
                  <th scope="col">技術</th>
                  <th scope="col">経験年数</th>
                  <th scope="col">スキル</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <th scope="row">AWS</th>
                  <td>半年〜１年未満</td>
                  <td>
                    <p>EC２</p>
                  </td>
                </tr>
                <tr>
                  <th scope="row">Github</th>
                  <td>半年</td>
                  <td>
                    <p>チームでのgitフロー</p>
                  </td>
                </tr>
                <tr>
                  <th scope="row">Docker</th>
                  <td>半年未満</td>
                  <td>
                    <span class="rating">
                      <p class="rate rate4"></p>
                    </span>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>

      <NuxtLink to="/about">
        <P class="font-blue-bold">詳細はこちら</P>
      </NuxtLink>
    </div>
  </section>
</template>

    
<style>
.card {
  margin: 20px;
}
</style>
<script>
export default {
  el: '#app',
  methods: {
    handleScroll: function(evt, el) {
      if (window.scrollY > 50) {
        el.setAttribute(
          'style',
          'opacity: 1; transform: translate3d(0, -10px, 0)'
        )
      }
      return window.scrollY > 100
    }
  }
}
</script>
<style>
.font-blue-bold {
  color: deepskyblue;
  text-align: right;
  font-weight: bolder;
}
</style>

