<template>
    <div>
        <section>
            <div class="Prime-section">
                <h1>Contenuto</h1>
            </div>
        </section>
             <!-- ------------Divisone---------- -->
        <section>
            <div class="Second-section">
                <div class="imgContainer"><img src="../assets/img/buy-comics-digital-comics.png" alt="">asd</div>
                <div class="imgContainer"><img src="../assets/img/buy-comics-digital-comics.png" alt=""></div>
                <div class="imgContainer"><img src="../assets/img/buy-comics-digital-comics.png" alt=""></div>
                <div class="imgContainer"><img src="../assets/img/buy-comics-digital-comics.png" alt=""></div>
                <div class="imgContainer"><img src="../assets/img/buy-comics-digital-comics.png" alt=""></div>
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
    .Prime-section{
        background-color: rgb(0, 0, 146);
        width: 100%;
        height: 20vh;
        display: flex;
        align-items: center;
        
        h1{
            color: white;
            font-size: 2.3rem;
        }
    }

    // -------------------Divisione-----------

    .Second-section{
        background-color: rgb(0, 174, 255);
        width: 100%;
        height: 20vh;
        display: flex;
        justify-content: space-between;
        
        

        .imgContainer img{
            max-height: 70px;
            max-width:  70px;
            
        }
    }
</style>