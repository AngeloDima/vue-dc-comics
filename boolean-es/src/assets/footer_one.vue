<template>
    <div>
        <section id="sectionOne">

            <div class="ListaInfo">
                <h4>DC COMICS</h4>
                <ul>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                </ul>

                <h4>DC COMICS</h4>
                <ul>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                </ul>

                <h4>DC COMICS</h4>
                <ul>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                </ul>

                <h4>DC COMICS</h4>
                <ul>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                </ul>
            </div>

            <div class="logoDcTrasparente">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </section>
    </div>
</template>

<script>
export default{
    Name: `footer_one`,
}
</script>

<style lang="scss" scoped>
    #sectionOne{
        background-image: url(../assets/img/footer-bg.jpg);
        background-size: cover;
        width: 100%;
        height: 50vh;
        display: flex;
        justify-content: space-around;
        

         .logoDcTrasparente img{   
             width: 100%;
             height: 100%;
             position: relative;
            right: 20%;
         }
    }

    .ListaInfo{
        display: flex;
        flex-wrap: wrap;
        width: 40%;
        height: 100%;
        background-color: rgba(255, 255, 255, 0.767);
        ul{
            li{
                list-style: none;
            }
        }
    }
</style>