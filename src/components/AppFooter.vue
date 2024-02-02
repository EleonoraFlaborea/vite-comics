<script >
export default {
    name: 'AppFooter'
}
</script>

<template>
    <nav class="footer-container">
        <ul>
            <li>
                <h3>DC COMICS</h3>
            </li>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>

            <li>
                <h3>SHOP</h3>
            </li>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
        </ul>

        <ul>
            <li>
                <h3>DC</h3>
            </li>
            <li><a href="#">Terms of use</a></li>
            <li><a href="#">Privacy policy (New)</a></li>
            <li><a href="#">Ad Chices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>
        </ul>

        <ul>
            <li>
                <h3>SITES</h3>
            </li>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>


        </ul>
    </nav>
</template>

<style lang="scss">
.footer-container {
    display: flex;
    min-height: 500px;
    padding-left: 250px;
    background-image: url('../assets/img/footer-bg.jpg');
    padding-top: 50px;
}

a {
    text-decoration: none;
    color: white;
}

ul {
    list-style-type: none;
}

li {
    padding: 5px 20px;
}

h3 {
    color: white;
    font-size: 25px;
}
</style>