<template>
    <div>
        <section id="SecOne">
            <div class="Prime-section">
                <h1>Contenuto</h1>
            </div>
        </section>
             <!-- ------------Divisone---------- -->
        <section id="SecTwo">
            <div class="Second-section">
                <div class="imgContainer"><img src="../assets/img/buy-comics-digital-comics.png" alt=""><h5>DIGITAL COMICS</h5></div>
                <div class="imgContainer"><img src="../assets/img/buy-comics-merchandise.png" alt=""><h5>DC MERCHANDISE</h5></div>
                <div class="imgContainer"><img src="../assets/img/buy-comics-subscriptions.png" alt=""><h5>SUBSCRIPTION</h5></div>
                <div class="imgContainer"><img src="../assets/img/buy-comics-shop-locator.png" alt=""><h5>COMIC SHOP LOCATOR</h5></div>
                <div class="imgContainer"><img src="../assets/img/buy-dc-power-visa.svg" alt=""><h5>DC POWER VISA</h5></div>
            </div>
        </section>
    </div>
</template>

<script>
export default{
    Name: `main_one`,
}
</script>

<style lang="scss" scoped>
    #SecOne{
        background-color: hsl(0deg 0% 11%);
    }
    #SecTwo{
        background-color: hsl(209deg 98% 49%);
    }

    .Prime-section{
        
        width: 70%;
        height: 10vh;
        display: flex;
        align-items: center;
        margin: auto;
        
        h1{
            color: white;
            font-size: 2.3rem;
        }
    }

    // -------------------Divisione-----------

    .Second-section{

        width: 70%;
        height: 10vh;
        display: flex;
        justify-content: space-between;
        margin: auto;
        
        .imgContainer{
            display: flex;
            align-items: center;
            h5{
                margin-left: 20px;
                font-size: 0.7rem;
                color: white;
                font-weight: 600;
            }
        }
        .imgContainer img{
            max-height: 50px;
            width: 50px;
            ;
            
        }
    }
</style>