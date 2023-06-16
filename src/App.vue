<template>
<div class="container">
    <h1>Counter: {{counter}}</h1>
    <div class="d-flex">
        <button @click="onInc" class="btn btn-success">ADD</button>
        <button @click="onDec" class="btn btn-danger">Del</button>
    </div>
</div> 
</template>

<script>
export default {
    data() {
        return {
            counter: 0,
        }
    },
    methods: {
        onInc() {
            this.counter += 1
        },
        onDec() {
            this.counter -= 1
        }
    }
}
</script>

<style>

</style>
