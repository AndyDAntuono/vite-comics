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
                <div class="col-12">
                    <div class="jumbotron">
                    </div>
                </div>
            </div>
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

.jumbotron {
    background-image: url('../assets/img/jumbotron.jpg');
    height: 300px; /* Anche qui ho dovuto impostare un altezza fissa poiché altrimenti non mi appariva l'immagine essendo il div jumbotron fondamentalmente vuoto */
    background-size: cover; 
    background-position: top;
}

</style>
