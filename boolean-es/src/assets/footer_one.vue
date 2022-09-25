<template>
    <div>
        <section id="sectionOne">

            <div class="ListaInfo">
                
                <ul>
                    <h4>DC COMICS</h4>
                    <li><a href="">Characters</a></li>
                    <li><a href="">Comics</a></li>
                    <li><a href="">Movies</a></li>
                    <li><a href="">TV</a></li>
                    <li><a href="">Games</a></li>
                    <li><a href="">Videos</a></li>
                    <li><a href="">News</a></li>
                </ul>

                
                <ul>
                    <h4>DC</h4>
                    <li><a href="">Terms Of Use</a></li>
                    <li><a href="">Privacy policy (New)</a></li>
                    <li><a href="">Ad Choices</a></li>
                    <li><a href="">Advertising</a></li>
                    <li><a href="">Jobs</a></li>
                    <li><a href="">Subscriptions</a></li>
                    <li><a href="">Talent WorkShops</a></li>
                    <li><a href="">CPSC Certificates</a></li>
                    <li><a href="">Ratings</a></li>
                    <li><a href="">Shop Help</a></li>
                    <li><a href="">Contact Us</a></li>
                </ul>

                
                <ul>
                    <h4>SITES</h4>
                    <li><a href="">DC</a></li>
                    <li><a href="">MAD Magazine</a></li>
                    <li><a href="">DC Kids</a></li>
                    <li><a href="">DC Universe</a></li>
                    <li><a href="">DC Power Visa</a></li>
                </ul>

                
                <ul id="Ul-up">
                    <h4>SHOP</h4>
                    <li><a href="">Shop DC</a></li>
                    <li><a href="">Shop DC Collectibles</a></li>
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
      *{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

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
        position: relative;
        display: flex;
        flex-wrap: nowrap;
        gap: 50px;
        width: 40%;
        height: 100%;
        // background-color: rgba(255, 255, 255, 0.767);
        ul{
            display:block;
            h4{
                color: white;
            }
            li{
                list-style: none;
                margin: 10px 0px;
                a{
                    text-decoration: none;
                    color: rgb(117, 117, 117);
                    
                }
            }
        }
        #Ul-up{
            // background-color: red;
            position: absolute;
            bottom: 50px;
        }
    }
</style>