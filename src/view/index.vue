<template>
    <div class="container">
        <!--<topComponent :title='appName' :showLeft='false'></topComponent>-->
        <loanBanner></loanBanner>

        <videos></videos>
    </div>
</template>

<script>
    //import someComponent from './someComponent'
    // 引入banner组件
    import loanBanner from '../components/loan/banner'
    import videos from '../components/video/index'
    export default {
        name: "",
        data(){
            return {
                msg: "Hello Vue.js"
            }
        },
        components: {
            loanBanner,videos
        }
    }
</script>