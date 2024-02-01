<script >
export default {
    name: 'AppHeader'
}
</script>

<template>
    <!--HEADER-->
    <header class="header-container">
        <figure class="logo-section">
            <img src="../assets/img/dc-logo.png" alt="dc-logo">
        </figure>
        <nav class="nav-section">
            <ul>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </nav>

    </header>
</template>

<style scoped>
a {
    text-decoration: none;
    color: black;

}

ul {
    list-style-type: none;
}

li {
    display: inline;
    padding: 0 10px;

}

/*header*/
.header-container {
    min-height: 60px;
    padding: 20px 10px;
    display: flex;
    align-items: center;
    justify-content: flex-end;
}

.logo-section {
    padding-left: 250px;
}
</style>