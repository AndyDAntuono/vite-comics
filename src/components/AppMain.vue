<script>
import comics from '../data/comics';

export default {
    data() {
        return {
            comics
        }
    }
}
</script>

<template>
    <main>
        <div class="container">
            <div class="row">
                <div class="col-2" v-for="comic, index in comics" :key="index">
                    <div class="card bg-black text-white">
                        <img :src="comic.thumb" :alt="comic.series">
                        <div class="card-body">
                            <div class="card-title"> {{ comic.series }}</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<style lang="scss" scoped>
main {
    background-color: black;
    color: white;
}
</style>
