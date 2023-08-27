<template>
    <div class="ResButton">
        <div class="Inner">
            <img src="/images/reshot-icon-resume-LAG8SUMQFZ.svg" alt="resume icon">
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
.ResButton{
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
            width: 50px;
        }
    }
}
</style>