<script>
export default {
    name: 'AppHeader',
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
    <header>
        <div class="container">
            <div class="row">
                <div class="logo">
                    <img src="/src/assets/img/dc-logo.png">
                </div>
                
                <nav>
                    <ul>
                        <li :class="{'active': link.active}" v-for="link in links">
                            <a href="#">{{ link.text }}</a>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
    <main>
        <div class="container">
            --> Contents goes here <--
        </div>
    </main>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;

.row {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
}

nav {
    display: flex;
    justify-content: center;


    ul {
        display: flex;

        li {
            padding: 10px;
            position: relative;

            &.active::after {
                content: '';
                width: 100%;
                height: 4px;
                background-color: black;
                position: absolute;
                left: 0;
                bottom:0;
            }

            a {
                font-size: 13px;
                color: black;
            }
        }
    }
}

main {
    background-color: rgba(0, 0, 0, 0.884);
    color: white;
    font-size: 25px;
    padding: 40px;
}

</style>