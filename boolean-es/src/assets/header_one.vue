<template>
    <div>
        <header>
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <ul>
                <li><a href="">CHARACTERS</a></li>
                <li><a href="">COMICS</a></li>
                <li><a href="">MOVIES</a></li>
                <li><a href="">TV</a></li>
                <li><a href="">GAMES</a></li>
                <li><a href="">COLLECTIBLES</a></li>
                <li><a href="">VIDEOS</a></li>
                <li><a href="">FANS</a></li>
                <li><a href="">NEWS</a></li>
                <li><a href="">SHOP</a></li>
            </ul>
        </header>
    </div>
</template>

<script>
export default{
    Name: `header_one`,
}
</script>

<style lang="scss" scoped>
    header{
        width: 70%;
        height: 15vh;
        // background-color: rgba(0, 195, 255, 0.432);
        margin: auto;

        display: flex;
        align-items: center;
        justify-content: space-between;
        
        img{
            width: 100px;
        }

        ul{
            display: flex;
            gap: 40px;
            text-decoration: none;
            font-size: 0.8rem;

            li{

                text-decoration: none;
                a{
                    text-decoration: none;
                }
            }
        }
    }
</style>