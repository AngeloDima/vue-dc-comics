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
                <div class="imgContainer"><img src="../assets/img/buy-comics-digital-comics.png" alt=""></div>
                <div class="imgContainer"><img src="../assets/img/buy-comics-merchandise.png" alt=""></div>
                <div class="imgContainer"><img src="../assets/img/buy-comics-subscriptions.png" alt=""></div>
                <div class="imgContainer"><img src="../assets/img/buy-comics-shop-locator.png" alt=""></div>
                <div class="imgContainer"><img src="../assets/img/buy-dc-power-visa.svg" alt=""></div>
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
        background-color: rgb(0, 0, 146);
    }
    #SecTwo{
        background-color: rgb(0, 195, 255);
    }

    .Prime-section{
        
        width: 80%;
        height: 20vh;
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
        
        width: 80%;
        height: 20vh;
        display: flex;
        justify-content: space-between;
        margin: auto;
        
        

        .imgContainer img{
            max-height: 70px;
            width: 70px;
            
        }
    }
</style>