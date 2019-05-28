<template>
  <section class="section has-text-white has-text-weight-bold has-background-grey-dark">
    <div class="container">
      <p class="title is-1 has-text-centered has-text-white" style="font-family: cursive;">PLOFILE</p>
      <div class="page-index">
        <div>
          <figure class="image is-128x128" style="margin: auto;">
            <img class="is-rounded" src="~@/assets/images/my-face.jpeg">
          </figure>
        </div>
        <h2 class="font-large-serif">樋口翔哉</h2>
        <div class="article-body">
          <p class="item delay-anime">
            はじめまして。平成10年生まれのエンジニアのヒグチと申します。</br>
            ２０１８年にプログラミングスクールのTECH::EXPERTでrailsを学んだのがプログラミングのスタートです</br>
            現在バイリンガルwebエンジニアとして活動中です‼ 寝る時間以外の８割はプログラミングうってます❗</br>
            ２３才からユタ州で大学生します💻 現在ベンチャーでエンジニアしつつ祝日にプログラミングスクールでメンターしてます</br>
            現場で書いているのはNuxt.jsやPHPを主に使っています</br>
            プログラミングスクールで教えている言語は主にjavascriptとrails</br>
            25歳までに起業する！</br>
          </p>
        </div>
        <h2 class="font-large-serif">主に使っている言語、ツール</h2>
        <div class="article-body item delay-anime">
          <p>(まだまだひよっこエンジニアです。。)</p>
          <ul>
            <li> Rails </li>
            <li> Nuxt.js(vue.js) </li>
            <li> wordpress </li>
            <li> AWS(EC2) </li>
            <li> Docker </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
@keyframes text-in {
  0% {
    transform: translate(10px, -120px);
    opacity: 0;
  }
}

.item {
  animation: text-in 4s cubic-bezier(0.12, 0.15, 0.5, 1.43) 0s backwards;
}
.font-large-serif {
  font-size: 30px;
  font-family: serif;
  color: aquamarine;
}
</style>

