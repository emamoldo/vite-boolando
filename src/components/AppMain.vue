<script>
export default {
    name: 'AppMain'
}
</script>

<template>
    <!--  Site Main  -->
    <div class="top_container">
        <ul class="relaxed_fit">
            <li>
                <img class="photo" src="../assets/img/1.webp" alt="">

                <div class="hover1">
                    <img class="photo" src="../assets/img/1b.webp" alt="">
                    <p>Levi's</p>
                    <strong>RELAXED FIT TEE UNISEX</strong>
                    <span class="discount_price">14.99€ <span class="normal_price">29.99€</span></span>
                </div>

                <div class="text">
                    <p>Levi's</p>
                    <strong>RELAXED FIT TEE UNISEX</strong>
                    <span class="discount_price">14.99€ <span class="normal_price">29.99€</span></span>
                </div>
            </li>
        </ul>

        <ul class="roses_tee">
            <li>
                <img class="photo" src="../assets/img/2.webp" alt="">

                <div class="hover1">
                    <img class="photo" src="../assets/img/2b.webp" alt="">
                    <p>Guess</p>
                    <strong>ROSES TEE</strong>
                    <span class="discount_price">20.99€ <span class="normal_price">29.99€</span></span>
                </div>

                <div class="text">
                    <p>Guess</p>
                    <strong>ROSES TEE</strong>
                    <span class="discount_price">20.99€ <span class="normal_price">29.99€</span></span>
                </div>
            </li>
        </ul>

        <ul class="sugar">
            <li>
                <img class="photo" src="../assets/img/3.webp" alt="">

                <div class="hover1">
                    <img class="photo" src="../assets/img/3b.webp" alt="">
                    <p>Come Zucchero Filato</p>
                    <strong>VOGLIA DI COLORI PASTELLO</strong>
                    <span class="discount_price">129.99€ <span class="normal_price">184.99€</span></span>
                </div>

                <div class="text">
                    <p>Come Zucchero Filato</p>
                    <strong>VOGLIA DI COLORI PASTELLO</strong>
                    <span class="discount_price">129.99€ <span class="normal_price">184.99€</span></span>
                </div>
            </li>
        </ul>
    </div>

    <div class="bottom_container">
        <ul class="tee_unisex">
            <li>
                <img class="photo" src="../assets/img/4.webp" alt="">

                <div class="hover1">
                    <img class="photo" src="../assets/img/4b.webp" alt="">
                    <p>Levi's</p>
                    <strong>TEE UNISEX</strong>
                    <span class="discount_price">14.99€ <span class="normal_price">29.99€</span></span>
                </div>

                <div class="text">
                    <p>Levi's</p>
                    <strong>TEE UNISEX</strong>
                    <span class="discount_price">14.99€ <span class="normal_price">29.99€</span></span>
                </div>
            </li>
        </ul>

        <ul class="stripe">
            <li>
                <img class="photo" src="../assets/img/5.webp" alt="">

                <div class="hover1">
                    <img class="photo" src="../assets/img/5b.webp" alt="">
                    <p>Maya Deluxe</p>
                    <strong>STRIPE BODICE</strong>
                    <span class="discount_price">99.99€</span>
                </div>

                <div class="text">
                    <p>Maya Deluxe</p>
                    <strong>STRIPE BODICE</strong>
                    <span class="discount_price">99.99€</span>
                </div>
            </li>
        </ul>

        <ul class="maglione">
            <li>
                <img class="photo" src="../assets/img/6.webp" alt="">

                <div class="hover1">
                    <img class="photo" src="../assets/img/6b.webp" alt="">
                    <p>Esprit</p>
                    <strong>MAGLIONE - NERO</strong>
                    <span class="discount_price">29.99€</span>
                </div>

                <div class="text">
                    <p>Esprit</p>
                    <strong>MAGLIONE - NERO</strong>
                    <span class="discount_price">29.99€</span>
                </div>
            </li>
        </ul>
    </div>
    <!-- /Site Main  -->
</template>

<style lang="scss">
/* Site Main */

// Color Palette
$discount-text: #fe0100;

.top_container,
.bottom_container {
    width: 1000px;
    margin: 0 auto;
    display: flex;
    justify-content: space-evenly;

    ul {
        list-style: none;
    }

    .photo {
        height: 400px;
        width: auto;
        padding-top: 3rem;

    }

    .text {
        display: flex;
        flex-direction: column;
    }

    .discount_price {
        color: $discount-text;
    }

    .normal_price {
        color: black;
    }
}


/* /Site Main */
</style>