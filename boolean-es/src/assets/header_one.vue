<template>
    <div>
        <header>
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
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
        width: 100%;
        height: 20vh;
        background-color: rgba(0, 195, 255, 0.432);
        img{
            width: 150px;
            height: 150px;
        }
    }
</style>