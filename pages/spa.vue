<template>
  <section class="container">
    <page-title>
      {{ meta.title }}
    </page-title>
    <nav class="page-nav">
      <page-nav-item
        v-for="spa in spas"
        :arg="spa"
        :key="spa.id"
      />
    </nav>
    <div class="content">
      <page-kv>
        <source slot="image" srcset="images/spa/J4-3-01.webp" type="image/webp">
        <img slot="image" data-src="images/spa/J4-3-01.jpg" alt="施術の様子">
      </page-kv>
      <p class="text">
        円庭施術院では外来のお客様の施術もお受け致します。トリートメントは予約制となっております。<br>
        ※表示されている価格は、２０１４年４月１日からのものです。<br>
        ※表示されている価格は税抜価格です。
      </p>
      <div class="wrap">
        <section class="section">
          <h3 class="section-title">
            ◇ 温泉/泉質 - カルシウム・ナトリウム硫酸塩温泉
          </h3>
          <p class="text">
            全ての施術の前にトリートメント効果を高めるために温泉入浴をお勧めしています。<br>
            また施術後には、白山の薬草や体質別の生薬を加えた温泉足浴をご用意しています。<br>
            温泉には主に「温熱効果」「水圧効果」「浮力効果」「薬理効果」などの効能があります。<br>
            「温熱効果」で体があたたまることにより、血液やリンパ液の流れが良くなり、新陳代謝が高まり、老廃物や疲労物質を排出できます。<br>
            「水圧効果」で血管が細くなり、足元に滞っていた血液が押し上げられ、血液の循環を促進。<br>
            横隔膜や肺が圧迫されるので呼吸回数が増え心肺機能が高まります。<br>
            「浮力効果」で筋肉や関節の負担が軽減され、筋肉が緩み、緊張が解き放たれリラックスできます。<br>
            「薬理効果」については、泉質はアルカリ性単純温泉で、美肌の湯と言われています。<br>
            効能は、神経痛、筋肉痛、関節痛、五十肩、関節のこわばり、うちみ、くじき、慢性消化器病、痔疾、冷え症、病後回復期、健康増進などです。<br>
          </p>
        </section>
        <section class="section">
          <h3 class="section-title">
            ◇ 薬草マトリックス「補捨流調」
          </h3>
          <p class="text">
            薬草には元気を補い「補」、余分なものを捨て「捨」、流れをさらさらにし「流」、からだ全体のバランスを調える「調」、などの力があります。ひとりひとりの体調やご希望、たとえば免疫力の向上「本」、気持ちの安定「心」、長寿「寿」、美容と美肌「美」にあわせて薬草をお選びし、薬草玉や煎じ生薬・薬草茶などに使用いたします。
          </p>
          <div class="image-list animation-trigger1">
            <picture>
              <source class="image-list__item animation-target1 animation-target" srcset="images/spa/J4-3-02.webp" type="image/webp">
              <img class="image-list__item animation-target1 animation-target" src="images/spa/J4-3-02.jpg" alt="">
            </picture>
          </div>
          <div class="image-list animation-trigger2">
            <picture>
              <source class="image-list__item animation-target1 animation-target" srcset="images/spa/J4-3-03.webp" type="image/webp">
              <img class="image-list__item animation-target2 animation-target" src="images/spa/J4-3-03.jpg" alt="">
            </picture>
          </div>
          <div class="image-list animation-trigger3">
            <picture>
              <source class="image-list__item animation-target1 animation-target" srcset="images/spa/J4-3-04.webp" type="image/webp">
              <img class="image-list__item animation-target3 animation-target" src="images/spa/J4-3-04.jpg" alt="">
            </picture>
          </div>
        </section>
        <section class="section">
          <h3 class="section-title">
            ◇「薬師山」と「円庭施術院」
          </h3>
          <p class="text">
            山代温泉の歴史は霊峰白山との深いつながりの中で育まれてきました。平安時代、加賀には白山五院が建立され、白山信仰の中心的役割を担うようになります。山代の薬王院温泉寺は白山五院の筆頭寺院として栄え、寺のあった場所はその霊性の高さから「薬師山」と呼ばれ、僧たちが修行や学問に励むと同時に、温泉の施浴と薬草の調合で人々を救っていた治療の場でもあったと語り継がれています。べにや無何有は、この白山信仰の聖地「薬師山」の高台、薬王院温泉寺の本堂の跡地に静かにたたずむ湯宿です。古来より僧侶が温泉の施浴と薬草の調合により人々を癒してきた「薬師山」の伝統を受け継ぎ、宿のスパ「円庭施術院」では温泉と薬草を用いた「薬師山トリートメント」をはじめ各種トリートメントで心身のケアを行っています。
          </p>
        </section>
      </div>
      <div class="wrap">
        <section class="section">
          <h3 class="section-title">
            一、薬師山フェイシャルトリートメント
          </h3>
          <p class="text">
            薬草マトリックス「補捨流調」を用いてカウンセリングを行い、ひとりひとりの体質や体調に合わせてオーダーメイドの「薬草玉」と「漢方クリーム」を調合いたします。さらにお客様の体調やご要望に合わせてセラピストがオーダーメイドのマッサージ（スリミング、リラクゼーション、疲労回復、等）をご提案させていただきます。マッサージを行った後、蒸し上げた薬草玉を身体に押し当てていきます。円庭施術院オリジナルの「薬草玉」と「漢方クリーム」により薬草成分がたっぷりと体内に吸収され、体調を整えます。
          </p>
          <p class="text">
            ※薬草玉―生薬を晒しで包んで蒸し上げたもの<br>
            ※漢方クリーム―煎じ生薬+山代温泉水+漢方オイル+二十四種類の薬草を配合したオンクチュウクリーム
          </p>
          <ul class="plan-nav">
            <li class="plan-nav__list">
              <ul class="plan-nav-detail">
                <li class="plan-nav-detail__time">
                  ７０分
                </li>
                <li class="plan-nav-detail__menu">
                  ボディ（背面のみ）・デコルテ ＋ 薬草玉
                </li>
                <li class="plan-nav-detail__price">
                  １７，０００円
                </li>
              </ul>
            </li>
            <li class="plan-nav__list">
              <ul class="plan-nav-detail">
                <li class="plan-nav-detail__time">
                  ９０分
                </li>
                <li class="plan-nav-detail__menu">
                  ボディ・デコルテ・ネック ＋ 薬草玉
                </li>
                <li class="plan-nav-detail__price">
                  ２１，０００円
                </li>
              </ul>
            </li>
            <li class="plan-nav__list">
              <ul class="plan-nav-detail">
                <li class="plan-nav-detail__time">
                  １２０分
                </li>
                <li class="plan-nav-detail__menu">
                  ボディ・デコルテ・ネック・フィトヘッド ＋ 薬草玉
                </li>
                <li class="plan-nav-detail__price">
                  ２４，０００円
                </li>
              </ul>
            </li>
          </ul>
        </section>
      </div>
      <div class="wrap">
        <section class="section">
          <h3 class="section-title">
            一、薬師山フェイシャルトリートメント
          </h3>
          <p class="text">
            薬草マトリックス「補捨流調」を用いてカウンセリングを行ない、ひとりひとりの体質や体調に合わせて配合した「薬草玉」と「煎じ生薬漢方ゴマージュ」を調合いたします。「煎じ生薬漢方ゴマージュ」にて肌のくすみを取り去り、薬草成分と温泉成分を吸収させます。むくみや疲れを取り去りフェイスラインをすっきりと整えるリフトアップマッサージの後、蒸し上げた「薬草玉」を首まわりや肩などに押し当てていきます。リフトアップマッサージには無何有オリジナル「薬師山アメニティー」スキンケアラインの「薬師山エマルジョン（美容液と乳液をミックスさせたスペシャルケア・エッセンス）」を使用。ダメージを受けた肌に栄養を与えていきます。仕上げには「薬師山ローション」と「薬師山エマルジョン」及びプラセンタエキスを贅沢に配合し美白効果・エイジングケアに優れた「薬師山エイジングケアライン」をプラスし、若々しく弾力のある肌へと導きます。<br>
            ＊全てのコースにデコルテ・ヘッドマッサージが含まれています。
          </p>
          <ul class="plan-nav">
            <li class="plan-nav__list">
              <ul class="plan-nav-detail">
                <li class="plan-nav-detail__time">
                  ７０分
                </li>
                <li class="plan-nav-detail__menu">
                  洗顔・漢方ゴマージュ・フェイシャルマッサージ・薬草玉・整肌
                </li>
                <li class="plan-nav-detail__price">
                  １７，０００円
                </li>
              </ul>
            </li>
            <li class="plan-nav__list">
              <ul class="plan-nav-detail">
                <li class="plan-nav-detail__time">
                  ９０分
                </li>
                <li class="plan-nav-detail__menu">
                  洗顔・漢方ゴマージュ・フェイシャルマッサージ・ハンドマッサージ・薬草玉・整肌
                </li>
                <li class="plan-nav-detail__price">
                  １９，０００円
                </li>
              </ul>
            </li>
            <li class="plan-nav__list">
              <ul class="plan-nav-detail">
                <li class="plan-nav-detail__time">
                  １２０分
                </li>
                <li class="plan-nav-detail__menu">
                  洗顔・薬草ゴマージュ・フェイシャルマッサージ・ハンドマッサージ・薬草玉・整肌・フィトヘッド
                </li>
                <li class="plan-nav-detail__price">
                  ２３，０００円
                </li>
              </ul>
            </li>
          </ul>
        </section>
      </div>
      <div class="wrap">
        <section class="section">
          <h3 class="section-title">
            一、薬師山ボディ&amp;フェイシャルトリートメント
          </h3>
          <p class="text">
            薬師山ボディトリートメントと薬師山フェイシャルトリートメントを組み合わせたお得なコースです。<br>
            内容の詳細につきましては薬師山ボディトリートメント、薬師山フェイシャルトリートメントメニューをご参照ください。
          </p>
          <ul class="plan-nav">
            <li class="plan-nav__list">
              <ul class="plan-nav-detail">
                <li class="plan-nav-detail__time">
                  ９０分
                </li>
                <li class="plan-nav-detail__menu">
                  ボディ（背中）または脚 ＋ フェイシャル
                </li>
                <li class="plan-nav-detail__price">
                  ２５，０００円
                </li>
              </ul>
            </li>
            <li class="plan-nav__list">
              <ul class="plan-nav-detail">
                <li class="plan-nav-detail__time">
                  １２０分
                </li>
                <li class="plan-nav-detail__menu">
                  ボディ（背中） 及び 脚 ＋ フェイシャル
                </li>
                <li class="plan-nav-detail__price">
                  ２８，０００円
                </li>
              </ul>
            </li>
            <li class="plan-nav__list">
              <ul class="plan-nav-detail">
                <li class="plan-nav-detail__time">
                  １２０分
                </li>
                <li class="plan-nav-detail__menu">
                  洗顔・薬草ゴマージュ・フェイシャルマッサージ・ハンドマッサージ・薬草玉・整肌・フィトヘッド
                </li>
                <li class="plan-nav-detail__price">
                  ２３，０００円
                </li>
              </ul>
            </li>
          </ul>
        </section>
      </div>
    </div>
    <div class="cards animation-trigger4">
      <Card
        v-for="spa in spas"
        :arg="spa"
        :key="spa.id"
        class="animation-target4 animation-target"
      />
    </div>
  </section>
</template>

<script>
import PageTitle from '~/components/PageTitle.vue'
import PageKv from '~/components/PageKv.vue'
import PageNavItem from '~/components/PageNavItem.vue'
import Card from '~/components/Card.vue'
import Data from '~/store/data.json'
import Meta from '~/assets/js/meta.js'

export default {
  components: {
    PageTitle,
    PageKv,
    PageNavItem,
    Card
  },
  mixins: [Meta],
  data () {
    return {
      meta: {
        title: 'スパ 円庭施術院',
        description: 'スパ 円庭施術院のディスクリプション。加賀山代温泉、薬師山の高台に静かにたたずむ宿。宿の名の「無何有」とは空っぽの中の豊かさという意味。静かで平和な時間が流れています。',
        type: 'article',
        url: 'https://mukayu.com/reservation',
        image: 'https://mukayu.com/img/ogp/reservation.jpg'
      }
    }
  },
  asyncData (context) {
    return {
      spas: Data.spas
    }
  },
  mounted () {
    const scene1 = this.$scrollmagic
      .scene({
        triggerElement: '.animation-trigger1',
        triggerHook: 'onEnter',
        offset: 100,
        reverse: false
      })
      .setTween('.animation-target1', {
        css: {
          opacity: '1',
          transform: 'translateY(0)'
        }
      })
    this.$scrollmagic.addScene(scene1)

    const scene2 = this.$scrollmagic
      .scene({
        triggerElement: '.animation-trigger2',
        triggerHook: 'onEnter',
        offset: 100,
        reverse: false
      })
      .setTween('.animation-target2', {
        css: {
          opacity: '1',
          transform: 'translateY(0)'
        }
      })
    this.$scrollmagic.addScene(scene2)

    const scene3 = this.$scrollmagic
      .scene({
        triggerElement: '.animation-trigger3',
        triggerHook: 'onEnter',
        offset: 100,
        reverse: false
      })
      .setTween('.animation-target3', {
        css: {
          opacity: '1',
          transform: 'translateY(0)'
        }
      })
    this.$scrollmagic.addScene(scene3)

    const scene4 = this.$scrollmagic
      .scene({
        triggerElement: '.animation-trigger4',
        triggerHook: 'onEnter',
        offset: 100,
        duration: 500,
        reverse: false
      })
      .setTween('.animation-target4', {
        css: {
          opacity: '1',
          transform: 'translateY(0)'
        }
      })
    this.$scrollmagic.addScene(scene4)
  }
}
</script>

<style lang="scss" scoped>
  .wrap {
    padding: 60px 0;
    border-top: 1px solid $text-color;

    @include media(md, max) {
      padding: 30px 0;
    }
  }

  .section {
    &:not(:first-child) {
      margin: 60px 0 0;

      @include media(md, max) {
        margin: 30px 0 0;
      }
    }
  }

  .section-title {
    font-size: $fts-xx-large;

    @include media(md, max) {
      font-size: $fts-x-large;
    }
  }

  .plan-nav__list {
    &:not(:first-child) {
      margin: 20px 0 0;
    }
  }

  .plan-nav-detail {
    @include flex(wrap, flex-start, flex-start);

    @include media(md, max) {
      @include flex(wrap, space-between, flex-start);
    }

    &__time {
      width: 60px;
    }

    &__menu {
      width: calc(95% - 60px - 200px);
      text-indent: -10px;
      margin: 0 0 0 26px;

      @include media(md, max) {
        width: calc(90% - 60px);
      }

      &::before {
        display: inline-block;
        content: "ー";
        color: $text-color;
      }
    }

    &__price {
      width: 200px;
      margin: 0 0 0 20px;

      @include media(md, max) {
        width: calc(100% - 90px);
        margin: 0 0 0 90px;
      }
    }
  }
  .animation-target {
    opacity: 0;
    transform: translateY(50px);
    transition: all 0.4s $fadeCubic;
  }
</style>
