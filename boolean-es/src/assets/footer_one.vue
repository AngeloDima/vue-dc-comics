<template>
    <div>
        <section id="sectionOne">
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
        justify-content: end;

         .logoDcTrasparente img{   
             width: 100%;
             height: 100%;
         }
    }
</style>