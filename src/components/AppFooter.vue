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

            </div>
        </div>
        <!-- <img src="/src/assets/img/footer-bg.jpg" alt="">
        <nav>
            <ul>
                <li :class="{'active': link.active}" v-for="link in links">
                    <a href="#">{{ link.text }}</a>
                </li>
            </ul>
        </nav> -->
    </footer>
</template>

<style lang="scss" scoped>
@use '../style/partials/variables' as *;
footer {
    padding: 20px 0;
    background-image: url('../assets/img/footer-bg-jpeg');
}
</style>