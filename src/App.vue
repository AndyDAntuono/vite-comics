<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>
<template lang="">
    <div>
        <AppHeader />
        <AppMain />
        <AppFooter />
    </div>
</template>

<!--scrivendo come segue si importa come si deve generals.scss-->
<style lang="scss">
@use './styles/generals.scss';
</style>