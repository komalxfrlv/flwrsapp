<template>
    <footer>
        <div class="footer-holder">
            <nav class="flex-container">
                <div class="flex-item">
                    <router-link to="/">Студия</router-link>
                </div>
                <div class="flex-item">
                    <router-link to="/profile">Профиль</router-link>
                </div>
            </nav>
        </div>
    </footer>
</template>

<style lang="scss">
nav {
    padding: 30px;

    a {
        font-weight: bold;
        color: #ffffff;
        text-decoration: none;

        &.router-link-exact-active {
            color: #fff;
            text-decoration: underline;
        }
    }
}

footer {
    position: fixed;
    bottom: 0;
    width: 100%;
}

.footer-holder {
    padding: 10px;
    background-color: #42b983;
}

.flex-container {
    padding: 0;
    margin: 0;

    display: -webkit-box;
    display: -moz-box;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;

    flex-flow: row wrap;
    justify-content: space-around;

    .flex-item {
        padding: 5px;
        color: white;
        font-weight: bold;
        text-align: center;
    }
}
</style>