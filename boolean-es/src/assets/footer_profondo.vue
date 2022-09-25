<template>
    <section id="SecOne">
        <div class="container">
            <input type="submit" value="SIGN-UP NOW!">
            <div class="container-mini">
                <span id="Follow">FOLLOW US</span>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </section>
</template>

<script>
    export default{
    Name: `footer_profondo`,
}
</script>

<style lang="scss" scoped>
    #SecOne{
        background-color: hsl(0deg 0% 19%);
        width: 100%;
        height: 13vh;
    }
    .container{
        width: 80%;
        
        margin: auto;
        display: flex;
        justify-content: space-between;
    
        input{
            padding: 17px;
            background-color: rgba(255, 0, 0, 0);
            border: 2px solid hsl(209deg 98% 49%);
            color: white;
            margin-top: 35px;
        }
        .container-mini{
            #Follow{
                color: hsl(209deg 98% 49%);
                font-size: 1.2rem;
                
                position: relative;
                bottom: 10px;
                right: 15px;
            }
            img{
                margin: 0px 10px;
                margin-top: 35px;
            }
        }

    }
</style>