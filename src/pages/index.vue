<template>
  <div>
      sjffjsguwufgusgjgsugusuhusghuhguh
      <img src="../assets/640x480_Mobile.jpg" alt="">
      <hheader></hheader>
  </div>
</template>

<script>
import Hheader from '~components/Hheader.vue';
export default {
    data() {
        return {
            title: 'Hello',
        };
    },
    head () {
        return {
            title: this.title,
        };
    },
    components: {
        Hheader,
    },
};
</script>

<style lang="scss">

</style>

