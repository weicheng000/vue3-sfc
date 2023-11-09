<template>
    <div>
        <h1>{{ msg }}</h1>
        <counter-button></counter-button>
        <counter-button></counter-button>
    </div>
</template>
<script>
import CounterButton from './compoents/button.vue';
export default {
    components:{
        CounterButton
    },
    data(){
        return{
            msg: "hello sfc!"
        }
    }
}
</script>
