<template>
    <section id="SecOne">
        <div class="container">
            <input type="submit" value="SIGN-UP NOW!">
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
    
        input{
            padding: 17px;
            background-color: rgba(255, 0, 0, 0);
            border: 2px solid hsl(209deg 98% 49%);
            color: white;
            margin-top: 35px;
        }
    }
</style>