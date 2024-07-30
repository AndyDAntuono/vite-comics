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
                    <h1>Contenuto di main</h1>
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
