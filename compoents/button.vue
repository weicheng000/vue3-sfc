<template>
    <div>
        <button type="button" @click="click">Counter: {{ counter }}</button>
    </div>
</template>
<script>
export default{
    data(){
        return{
            counter: 0
        }
    },
    methods: {
        click(){
            this.counter++
        }
    }
}
</script>