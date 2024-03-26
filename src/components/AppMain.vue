<script>
export default {
    name: 'AppMain',

    data() {
        return {
            products: [
                {
                    "id": 1,
                    "frontImage": "1.webp",
                    "backImage": "1b.webp",
                    "brand": "Levi's",
                    "name": "Relaxed Fit",
                    "price": 29.99,
                    "isInFavorites": true,
                    "badges": [
                        {
                            "type": "tag",
                            "value": "Sostenibilità"
                        },
                        {
                            "type": "discount",
                            "value": "-50%"
                        }
                    ]
                },
                {
                    "id": 2,
                    "frontImage": "2.webp",
                    "backImage": "2b.webp",
                    "brand": "Guess",
                    "name": "Roses Tee",
                    "price": 20.99,
                    "isInFavorites": true,
                    "badges": [
                        {
                            "type": "discount",
                            "value": "-30%"
                        }
                    ]
                },
                {
                    "id": 3,
                    "frontImage": "3.webp",
                    "backImage": "3b.webp",
                    "brand": "Come Zucchero Filato",
                    "name": "Voglia di colori pastello",
                    "price": 129.99,
                    "isInFavorites": false,
                    "badges": [
                        {
                            "type": "discount",
                            "value": "-30%"
                        }
                    ]
                },
                {
                    "id": 4,
                    "frontImage": "4.webp",
                    "backImage": "4b.webp",
                    "brand": "Levi's",
                    "name": "Tee Unisex",
                    "price": 14.99,
                    "isInFavorites": false,
                    "badges": [
                        {
                            "type": "tag",
                            "value": "Sostenibilità"
                        },
                        {
                            "type": "discount",
                            "value": "-50%"
                        }
                    ]
                },
                {
                    "id": 5,
                    "frontImage": "5.webp",
                    "backImage": "5b.webp",
                    "brand": "Maya Deluxe",
                    "name": "Stripe Bodice",
                    "price": 99.99,
                    "isInFavorites": true,
                    "badges": [
                        {
                            "type": "tag",
                            "value": "Sostenibilità"
                        },
                        {
                            "type": "discount",
                            "value": "-50%"
                        }
                    ]
                },
                {
                    "id": 6,
                    "frontImage": "6.webp",
                    "backImage": "6b.webp",
                    "brand": "Esprit",
                    "name": "Maglione - Black",
                    "price": 29.99,
                    "isInFavorites": true,
                    "badges": [
                        {
                            "type": "tag",
                            "value": "Sostenibilità"
                        }
                    ]
                }
            ]
        }
    }
}

</script>

<template>
    <!--  Site Main  -->

    <!-- <ProductCard /> -->

    <!-- Product card -->

    <div class="top_container">
        <ul class="relaxed_fit">
            <li v-for="product in products">
                <img class="photo" :src="product.frontImage" alt="">
                <!-- need to fix the image in the script -->

                <div class="hover1">
                    <img class="photo" :src="product.backImage" alt="">
                    <p>{{ product.brand }}</p>
                    <strong>{{ product.name }}</strong>
                    <span class="discount_price">14.99€<span class="normal_price">{{ product.price }}</span></span>
                </div>

                <div class="text">
                    <p>{{ product.brand }}</p>
                    <strong>{{ product.name }}</strong>
                    <span class="discount_price">14.99€ <span class="normal_price">{{ product.price }}</span></span>
                </div>
            </li>
        </ul>
    </div>






    <!-- ORIGINAL FILE -->

    <!-- <div class="top_container">
        <ul class="relaxed_fit">
            <li>
                <img class="photo" src="../assets/img/1.webp" alt="">
                <div class="text">
                    <p>Levi's</p>
                    <strong>RELAXED FIT TEE UNISEX</strong>
                    <span class="discount_price">14.99€ <span class="normal_price">29.99€</span></span>
                </div>

                <div class="hover1">
                    <img class="photo" src="../assets/img/1b.webp" alt="">
                    <p></p>
                    <strong></strong>
                    <span class="discount_price">sconto<span class="normal_price">...</span></span>
                </div>
            </li>
        </ul>

        <ul class="roses_tee">
            <li>
                <img class="photo" src="../assets/img/2.webp" alt="">
                <div class="text">
                    <p>Guess</p>
                    <strong>ROSES TEE</strong>
                    <span class="discount_price">20.99€ <span class="normal_price">29.99€</span></span>
                </div>

                <div class="hover1">
                    <img class="photo" src="../assets/img/2b.webp" alt="">
                    <p>Guess</p>
                    <strong>ROSES TEE</strong>
                    <span class="discount_price">20.99€ <span class="normal_price">29.99€</span></span>
                </div>
            </li>
        </ul>

        <ul class="sugar">
            <li>
                <img class="photo" src="../assets/img/3.webp" alt="">
                <div class="text">
                    <p>Come Zucchero Filato</p>
                    <strong>VOGLIA DI COLORI PASTELLO</strong>
                    <span class="discount_price">129.99€ <span class="normal_price">184.99€</span></span>
                </div>

                <div class="hover1">
                    <img class="photo" src="../assets/img/3b.webp" alt="">
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
                <div class="text">
                    <p>Levi's</p>
                    <strong>TEE UNISEX</strong>
                    <span class="discount_price">14.99€ <span class="normal_price">29.99€</span></span>
                </div>

                <div class="hover1">
                    <img class="photo" src="../assets/img/4b.webp" alt="">
                    <p>Levi's</p>
                    <strong>TEE UNISEX</strong>
                    <span class="discount_price">14.99€ <span class="normal_price">29.99€</span></span>
                </div>
            </li>
        </ul>

        <ul class="stripe">
            <li>
                <img class="photo" src="../assets/img/5.webp" alt="">
                <div class="text">
                    <p>Maya Deluxe</p>
                    <strong>STRIPE BODICE</strong>
                    <span class="discount_price">99.99€</span>
                </div>

                <div class="hover1">
                    <img class="photo" src="../assets/img/5b.webp" alt="">
                    <p>Maya Deluxe</p>
                    <strong>STRIPE BODICE</strong>
                    <span class="discount_price">99.99€</span>
                </div>
            </li>
        </ul>

        <ul class="maglione">
            <li>
                <img class="photo" src="../assets/img/6.webp" alt="">
                <div class="text">
                    <p>Esprit</p>
                    <strong>MAGLIONE - NERO</strong>
                    <span class="discount_price">29.99€</span>
                </div>

                <div class="hover1">
                    <img class="photo" src="../assets/img/6b.webp" alt="">
                    <p>Esprit</p>
                    <strong>MAGLIONE - NERO</strong>
                    <span class="discount_price">29.99€</span>
                </div>
            </li>
        </ul>
    </div> -->
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