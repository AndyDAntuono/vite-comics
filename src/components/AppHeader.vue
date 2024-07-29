<script>
export default {
    data() {
        return {
            links: [
                {
                    label: 'CHARACTERS',
                    url: '#',
                    current: false
                },
                {
                    label: 'COMICS',
                    url: '#',
                    current: true
                },
                {
                    label: 'MOVIES',
                    url: '#',
                    current: false
                },
                {
                    label: 'TV',
                    url: '#',
                    current: false
                },
                {
                    label: 'GAMES',
                    url: '#',
                    current: false
                },
                {
                    label: 'COLLECTIBLES',
                    url: '#',
                    current: false
                },
                {
                    label: 'VIDEOS',
                    url: '#',
                    current: false
                },
                {
                    label: 'FANS',
                    url: '#',
                    current: false
                },
                {
                    label: 'NEWS',
                    url: '#',
                    current: false
                },
                {
                    label: 'SHOP',
                    url: '#',
                    current: false
                },
            ]
        }
    }
}
</script>
<template lang="">
    <header>
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="d-flex justify-content-between align-intems-center py-3 bg-white">
                        <img src="../assets/img/dc-logo.png" />
                        <nav class="navbar navbar-expand-lg">
                            <div class="container-fluid">
                                <div class="collapse navbar-collapse">
                                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                                        <li v-for="link, index in links" :key="index" :class="['nav-item', link.current ? 'active' : '']">
                                          <a class="nav-link" :href="link.url">{{ link.label }}</a>
                                        </li>
                                      </ul>
                                </div>
                            </div>
                        </nav>
                        <!--
                        <ul class="list-unstyled d-flex">
                            <li class="m1">CHARACTERS</li> 1
                            <li>COMICS</li> 2
                            <li>MOVIES</li> 3
                            <li>TV</li> 4
                            <li>GAMES</li> 5
                            <li>COLLECTIBLES</li> 6
                            <li>VIDEOS</li> 7
                            <li>FANS</li> 8
                            <li>NEWS</li> 9
                            <li>SHOP</li> 10
                        </ul>
                    -->
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
.nav-link {
    font-weight: bold;
    font-size: 20px;
}

.nav-item.active .nav-link {
    color: blue;
    border-bottom: 3px solid blue;
}
</style>