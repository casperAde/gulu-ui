<template>

  <div>

    <div>Button 示例</div>
    <Demo :component="Button1Demo"/>
    <Demo :component="Button2Demo"/>
    <Demo :component="Button3Demo"/>
    <Demo :component="Button4Demo"/>
    <Demo :component="Button5Demo"/>
  </div>
</template>

<script lang='ts'>
import Demo from './Demo.vue';
import Button1Demo from './Button1Demo.vue';
import Button2Demo from './Button2Demo.vue';
import Button3Demo from './Button3Demo.vue';
import Button4Demo from './Button4Demo.vue';
import Button5Demo from './Button5Demo.vue';

export default {
  components: {
    Demo
  },
  setup(){
    return {
      Button1Demo,
      Button2Demo,
      Button3Demo,
      Button4Demo,
      Button5Demo
    };
  }

};
</script>

<style lang='scss' scoped>
h1 {
  margin: 15px 0;
}

h1:first-child {
  margin-top: 0;
}
</style>