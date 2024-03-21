<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <!--  Page Header  -->
    <header>
        <div class="list">
            <div class="left_menu">
                <div>Uomo</div>
                <div>Donna</div>
                <div>Bambini</div>
            </div>

            <img class="logo" src="./assets/img/boolean-logo.png" alt="">

            <div class="right_menu">
                <div>
                    <i class="fa-regular fa-user"></i>
                </div>

                <div>
                    <i class="fa-regular fa-heart"></i>
                </div>

                <div>
                    <i class="fas fa-shopping-bag"></i>
                </div>
            </div>

        </div>
    </header>
    <!-- /Page Header  -->
</template>

<style lang="scss">
/* Site Header */

// Color Palette
$header: #ff6900;
$header-text: #ffffff;

.list {
    max-width: 1920px;
    height: 70px;
    background-color: $header;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.left_menu,
.right_menu {
    display: flex;
    color: $header-text;
    gap: 2rem;
}

.left_menu {
    margin-left: 10rem;
}

.right_menu {
    margin-right: 10rem;
}

.logo {
    display: flex;
    align-self: center;
    width: 150px;
}

/* /Site Header */
</style>
