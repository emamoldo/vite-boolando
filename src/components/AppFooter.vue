<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
    <!--  Site Footer -->
    <footer>
        <div class="footer">
            <h2>Booleando S.r.l.</h2>
            <div class="text_footer">
                <p>Informazioni Legali</p>
                <p>Informativa sulla privacy</p>
                <p>Diritto di recesso</p>
            </div>
        </div>

        <div class="right">
            <h4>Trovaci su</h4>
            <a href="#">
                <i class="fab fa-twitter fa-xs"></i>
            </a>
            <a href="#">
                <i class="fab fa-facebook fa-xs"></i>
            </a>
            <a href="#">
                <i class="fab fa-instagram fa-xs"></i>
            </a>
            <a href="#">
                <i class="fab fa-pinterest fa-xs"></i>
            </a>
            <a href="#">
                <i class="fab fa-youtube fa-xs"></i>
            </a>
        </div>

    </footer>
    <!-- /Site Footer -->
</template>

<style lang="scss">
/* Footer Page */

// Color Palette
$footer: #1b1b1a;
$header-text: #ffffff;


footer {
    margin-top: 2rem;
    height: 100px;
    display: flex;
    align-items: center;
    background-color: $footer;
    gap: 70rem;
}

.footer {
    margin: 0;
    margin-left: 10rem;
    color: $header-text;
    display: flex;
    flex-direction: column;
}

.text_footer {
    display: flex;
    gap: 1rem;
}

.right {
    color: $header-text;
}

.hover1 {
    display: none;
}

:hover+.hover1 {
    display: block;

}

/* /Site Footer */
</style>