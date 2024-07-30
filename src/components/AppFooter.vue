<script>
export default {
    
}
</script>

<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="d-flex justify-content-between align-items-center bg-primary text-white">
                        <div class="icon_and-text">
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                            <p>DIGITAL COMICS</p>
                        </div>
                        <div class="icon_and-text">
                            <img src="../assets/img/buy-comics-merchandise.png" alt="">
                            <p>DC MERCHANDISE</p>
                        </div>
                        <div class="icon_and-text">
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                            <p>SUBSCRIPTIONS</p>
                        </div>
                        <div class="icon_and-text">
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                            <p>COMIC SHOP LOCATOR</p>
                        </div>
                        <div class="icon_and-text">
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                            <p>DC POWER VISA</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row bg-footer">
                <div class="col-12">
                    <div class="d-flex flex-row mb-3 text-white">
                        <div class="p-2">
                            <ul class="list-unstyled">DC COMICS
                                <li><a href="">Characters</a></li>
                                <li><a href="">Comics</a></li>
                                <li><a href="">Movies</a></li>
                                <li><a href="">TV</a></li>
                                <li><a href="">Games</a></li>
                                <li><a href="">Videos</a></li>
                                <li><a href="">News</a></li>
                            </ul>
                            <ul class="list-unstyled">Shop
                                <li><a href="">Shop DC</a></li>
                                <li><a href="">Shop DC Collectibles</a></li>
                            </ul>
                        </div>
                        <div class="p-2">
                            <ul class="list-unstyled">DC
                                <li><a href="">Terms Of Use</a></li>
                                <li><a href="">Privacy policy (New)</a></li>
                                <li><a href="">Ad Choices</a></li>
                                <li><a href="">Advertising</a></li>
                                <li><a href="">Jobs</a></li>
                                <li><a href="">Subscriptions</a></li>
                                <li><a href="">Talent Workshops</a></li>
                                <li><a href="">CPSC Certificates</a></li>
                                <li><a href="">Ratings</a></li>
                                <li><a href="">Shop Help</a></li>
                                <li><a href="">Contac Us</a></li>
                            </ul>
                        </div>
                        <div class="p-2">
                            <ul class="list-unstyled">SITES
                                <li><a href="">DC</a></li>
                                <li><a href="">MAD Magazine</a></li>
                                <li><a href="">DC Kids</a></li>
                                <li><a href="">DC Universe</a></li>
                                <li><a href="">DC Power Visa</a></li>
                            </ul>
                        </div>
                      </div>
                </div>
            </div>
            <div class="row bg-secondary">
                <div class="col-12">
                    <div class="d-flex justify-content-between align-items-center">
                        <div class="sign-up_button m-1">SIGN UP</div>
                        <div class="d-flex justify-content-between align-items-center">
                            <div class="follow-us">
                                follow us
                            </div>
                            <img class="footer-icon" src="../assets/img/footer-facebook.png" alt="">
                            <img class="footer-icon" src="../assets/img/footer-twitter.png" alt="">
                            <img class="footer-icon" src="../assets/img/footer-youtube.png" alt="">
                            <img class="footer-icon" src="../assets/img/footer-pinterest.png" alt="">
                            <img class="footer-icon" src="../assets/img/footer-periscope.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
.icon_and-text img {
    /*ho dovuto ricorrere alle dimensioni fisse poiché quelle originali delle icone forniteci sono diverse*/
    max-width: 50 px;
    max-height: 100 px;
}

.bg-footer {
    background-image: url('../assets/img/dc-logo-bg.png'), url('../assets/img/footer-bg.jpg');
    background-position: right, left top;
    background-repeat: no-repeat, repeat;
    background-size: 30%, cover;
}

a {
    text-decoration: none;
    color: rgb(165, 165, 165);
}

a:hover {
    text-decoration: underline;
    color: rgb(38, 125, 175);
}

.sign-up_button {
    border: 1px solid blue;
    color: white;
}

.footer-icon {
    filter: invert(1) brightness(1.2) contrast(1.5);
}
</style>
