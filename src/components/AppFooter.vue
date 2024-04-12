<script>
export default {
    name: 'AppFooter',
    data() {
        return {
            links: [
                {
                    text: 'CHARACTERS',
                    active: false
                },
                {
                    text: 'COMICS',
                    active: true
                },
                {
                    text: 'MOVIES',
                    active: false
                },
                {
                    text: 'TV',
                    active: false
                },
                {
                    text: 'CHARACTERS',
                    active: false
                },
                {
                    text: 'COMICS',
                    active: true
                },
                {
                    text: 'MOVIES',
                    active: false
                },
                {
                    text: 'TV',
                    active: false
                },
                {
                    text: 'MOVIES',
                    active: false
                },
                {
                    text: 'TV',
                    active: false
                },
            ],
        }
    }
}
</script>

<template>
    <footer>
        <div class="footer-top">
            <div class="container">
                <nav>
                    <ul>
                        <li :class="{'active': link.active}" v-for="link in links">
                            <a href="#">{{ link.text }}</a>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use '../style/partials/variables' as *;
.footer-top {
    padding: 20px 0;
    background-image: url('../assets/img/footer-bg.jpg');

    .container {
        background-image: url('../assets/img/dc-logo-bg.png');
        background-position: 100%;
        background-repeat: no-repeat;
    }
}

</style>