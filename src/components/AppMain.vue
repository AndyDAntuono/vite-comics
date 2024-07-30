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
                <div class="col-2">
                    <div class="card">
                        <img src="" alt="">
                        <div class="card-body">
                            <div class="card-title"></div>
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
