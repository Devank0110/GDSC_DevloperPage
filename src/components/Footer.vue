<template>
    <v-footer padless class="">
        <v-card flat tile color="#222F37" width="100%" height="330px" class="mx-auto">
            <v-card-text>
                <div class="footer-dev pt-12">Developers</div>
            </v-card-text>
            <div class="pt-12 pb-3">
                <v-img class="gdsc-logo mx-auto" src="https://svgshare.com/i/nPe.svg"></v-img>
            </div>
            <v-card-text>
                <div class="footer-bits mx-auto">BITS Pilani</div>
            </v-card-text>

        </v-card>
    </v-footer>

</template>



<script>



export default {
    data: () => ({
        show: false,
    }),
}
</script>

<style>
.footer-dev {
    /* width: 212px; */
    /* height: 48px; */

    font-family: 'Google Sans';
    font-style: normal;
    font-weight: 500;
    font-size: 40px;
    line-height: 48px;
    /* identical to box height, or 120% */


    color: #FFFFFF;
}

.gdsc-logo {
    width: 575px;
    height: 35.62px;


    /* Inside auto layout */

    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
}

.footer-bits {
    width: 575px;
    height: 34px;

    font-family: 'Google Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 28px;
    line-height: 34px;
    /* identical to box height, or 121% */

    text-align: center;

    color: #D9D9D9;


    /* Inside auto layout */

    flex: none;
    order: 1;
    align-self: stretch;
    flex-grow: 0;
}
</style>