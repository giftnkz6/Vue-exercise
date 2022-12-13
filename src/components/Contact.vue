<template>
<div class="container">

    <div class="mb-3">
        <input type="name" class="form-control" id="exampleFormControlInput1" placeholder="Enter your Name">
    </div>
    <div class="mb-3">
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Enter your Surname">
    </div>
    <div class="mb-3">
        <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
    </div>
    <div>
        <button @click="greet" class="btn btn-primary" type="submit">Submit</button>
    </div>
</div>
</template>

<script>
    export default {
        name: "ContactPanel",
        methods:{
            greet() {
                alert("Lotjhani")
            }
        }
    }
</script>

<style>
    .container{
        width: 550px;
        margin-top: 2rem;
    }

</style>