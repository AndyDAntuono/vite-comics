<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default {
  components: {
    AppHeader,
    AppMain
  }
}
</script>
<template lang="">
    <div>
        <AppHeader />
        <AppMain />
    </div>
</template>

<!--scrivendo come segue si importa come si deve generals.scss-->
<style lang="scss">
@use './styles/generals.scss';
</style>