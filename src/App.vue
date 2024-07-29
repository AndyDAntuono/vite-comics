<script>
import AppHeader from './components/AppHeader.vue';

export default {
  components: {
    AppHeader
  }
}
</script>
<template lang="">
    <div>
        <AppHeader />
    </div>
</template>

<!--scrivendo come segue si importa come si deve generals.scss-->
<style lang="scss">
@use './styles/generals.scss';
</style>