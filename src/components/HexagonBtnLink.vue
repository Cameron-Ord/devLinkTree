<template>
    <div class="InButton">
        <div class="Inner">
            <img src="/images/iconmonstr-linkedin-3.svg" alt="github icon">
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
.InButton{
    display: grid;
    align-items: center;
    justify-items: center;
    >.Inner{
        display: grid;
        align-items: center;
        justify-items: center;
        background-color: #f6fff8;
        padding: 15px;
        border-radius: 50%;
        >img{
            border-radius: none;
            
            width: 50px;
        }
    }
}
</style>