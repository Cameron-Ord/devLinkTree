<template>
    <div class="MailButton">
        <div class="Inner">
            <img src="/images/mail-svgrepo-com.svg" alt="mail icon">
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
.MailButton{
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