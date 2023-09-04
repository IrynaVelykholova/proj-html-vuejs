<script>
import TheHeader from './components/TheHeader.vue';
import Slider from './components/Slider.vue';
import Illustrations from './components/Illustrations.vue';
import WorkingProcess from './components/WorkingProcess.vue';
import Work from './components/Work.vue';
import PreFooter from './components/PreFooter.vue';
import TheFooter from './components/TheFooter.vue';

export default {
    components:{
      TheHeader,
      Slider,
      Illustrations,
      WorkingProcess,
      Work,
      PreFooter,
      TheFooter,
    },
    data() {
      return {

      };
  },
}
</script>

<template>
<TheHeader></TheHeader>
<Slider></Slider>
<main>
  <Illustrations></Illustrations>
  <WorkingProcess></WorkingProcess>
  <Work></Work>
  <PreFooter></PreFooter>
</main>
<TheFooter></TheFooter>
</template>

<style scoped>

</style>
