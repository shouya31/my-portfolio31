<template>
  <section class="section">
    <div class="container">
      <div class="container title is-1" style="font-family: cursive;">
        <vue-typer text="MY WORKS"></vue-typer>
        <h2 class="subtitle">HELLO WORLD</h2>
      </div>
      <div class="columns">
        <div class="card column">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~@/assets/images/totokara.png" class="work_image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media">
              <div class="media-left"></div>
              <div class="media-content">
                <p class="title is-4">ととのえてからだ（受託）</p>
              </div>
            </div>

            <div class="content">
               『ととのえて、からだ』さんのホームページのリニューアル<br>
               主にwordpressを使い作りました
              <a
                href="https://tv.totokara.jp/"
              >
                <p>ホームページのリンクはこちら</p>
              </a>
            </div>
          </div>
        </div>

        <div class="card column">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~@/assets/images/mercari.jpg" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media">
              <div class="media-left"></div>
              <div class="media-content">
                <p class="title is-4">メルカリのコピーサイト</p>
              </div>
            </div>

            <div class="content">
              こちらはrailsとjQueryを主に使用して、メルカリに必要な<br>
            商品の出品　→　商品の購入　→　レビュー<br>
            といった必須の機能をメインに作り、ドメインをとってAWSによって本番環境にあげる
            というところまで実装しました   

              <a
                href="https://github.com/shouya31/freemarket_sample_42b"
              >
                <P>githubのurlはこちら</P>
              </a>
              <a href="https://www.freemaket42b.tk/">
                <p>実際のURLはこちら</p>
              </a>
            </div>
          </div>
        </div>
      </div>

      <div class="columns">
        <div class="card column">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~@/assets/images/chat-space.png" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media">
              <div class="media-left"></div>
              <div class="media-content">
                <p class="title is-4">chat-space</p>
              </div>
            </div>

            <div class="content">
              こちらは主にrailsとjQueryを使って、ラインのようなグループ機能だったり、ajax通信による
              非同期通信や自動更新に対応したチャットアプリです
              <a
                href="https://github.com/shouya31/chat-space5"
              >
                <P>githubのurlはこちら</P>
              </a>
              <a href="http://3.0.223.229/">
                <p>実際のURLはこちら</p>
              </a>
            </div>
          </div>
        </div>

        <div class="card column">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~@/assets/images/my-portfolio.png" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media">
              <div class="media-left"></div>
              <div class="media-content">
                <p class="title is-4">ポートフォリオ</p>
              </div>
            </div>

            <div class="content">
             こちらはフレームワークはNuxt.jsを使い静的なページを作りました
             CSSのフレームワークはbulmaを使っています
            </div>
          </div>
        </div>
      </div>
      <div class="columns">
        <div class="card column">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~@/assets/images/mooovi.jpeg" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media">
              <div class="media-left"></div>
              <div class="media-content">
                <p class="title is-4">mooovi</p>
              </div>
            </div>

            <div class="content">
              こちらは主にrailsによって、スクレイピングで映画の情報を取得して
              映画にレビューできるという機能を実装しました
              Ajax通信によるインクリメンタルサーチによってグーグル検索のようなリアルタイムに検索予想をたててくれる
              検索フォームを実装しました
            </div>
          </div>
        </div>

        <div class="card column">
          <div class="card-image">
            <figure class="image is-4by3">
              <img src="~@/assets/images/pictweet.jpeg" alt="Placeholder image">
            </figure>
          </div>
          <div class="card-content">
            <div class="media">
              <div class="media-left"></div>
              <div class="media-content">
                <p class="title is-4">pictweet</p>
              </div>
            </div>

            <div class="content">
              こちらは初めてrailsで作ったツイッターのようなツイートアプリになります<br>
              ユーザーのログイン機能やjQueryによる非同期通信など本当に基礎的な知識で作りました
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import { VueTyper } from 'vue-typer'
export default {
  components: {
    VueTyper
  }
}
</script>
<style>
.work_image {
  object-fit: cover;
}
</style>