<template>
    <div class="mainArch">
        <div>
            <article class="gitIcon">
                <hexagon-btn-git></hexagon-btn-git>
            </article>
            <article class="comBined">
                <div>
                    <hexagon-btn-link></hexagon-btn-link>
                </div>
                <div>
                    <hexagon-btn-res></hexagon-btn-res>
                </div>
            </article>
            <article class="mailIcon">
                <hexagon-btn-mail></hexagon-btn-mail>

            </article>
        </div>
    </div>
</template>

<script>
import HexagonBtnGit from '../components/HexagonBtnGit.vue';
import HexagonBtnLink from '../components/HexagonBtnLink.vue';
import HexagonBtnMail from '../components/HexagonBtnMail.vue';
import HexagonBtnRes from '../components/HexagonBtnRes.vue';


    export default {
        components:{
            HexagonBtnGit,
            HexagonBtnLink,
            HexagonBtnMail,
            HexagonBtnRes
        }
    }
</script>

<style lang="scss" scoped>
.mainArch{
    display: grid;
    min-height: 100vh;
    align-items: center;
    
    >div{
        display: grid;
        align-items: center;      
        grid-template-rows: 1fr 1fr 1fr;
        height: 225px;


        >.comBined{
            display: grid;
            align-items: center;
            justify-items: center;
            grid-template-columns: 1fr 1fr;
        }

    }
}

</style>