<template>
  <nuxt-link
    :to="arg.link"
    class="card animation-trigger1"
  >
    <figure class="figure animation-target1 animation-target">
      <client-only>
        <img v-lazy="`${arg.image}`" :alt="`${arg.title}イメージ`">
      </client-only>
      <figcaption class="figure-caption">
        {{ arg.title }}
      </figcaption>
    </figure>
  </nuxt-link>
</template>

<script>
export default {
  props: {
    arg: {
      type: Object,
      required: true
    }
  },
  mounted () {
    const scene1 = this.$scrollmagic
      .scene({
        triggerElement: '.animation-trigger1',
        triggerHook: 'onEnter',
        offset: 100,
        duration: 500,
        reverse: false
      })
      .setTween('.animation-target1', {
        css: {
          opacity: '1',
          transform: 'translateY(0)'
        }
      })
    this.$scrollmagic.addScene(scene1)
  }
}
</script>

<style lang="scss" scoped>
  .card {
    display: block;
    transition: all 0.3s $ease;

    &:hover {
      opacity: 0.7;
    }
  }
  .figure-image {
    display: block;
    height: auto;
  }
  .figure-caption {
    width: 100%;
    padding: 10px 15px;
    background: $black-color;
    color: $white-color;
    font-size: $fts-small;
    overflow: hidden;
    white-space: nowrap;
    text-overflow: ellipsis;
  }
  .animation-target {
    opacity: 0;
    transform: translateY(50px);
    transition: all 0.4s $fadeCubic;
  }
</style>
