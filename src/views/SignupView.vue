<script setup>

</script>
<template>
    <div class="signup">
        <div class="signup-form">
            <form>
                <div class="form-group row">
                    <label for="name" class="col-sm-2 col-form-label">Name</label>
                    <div class="col-sm-10 ">
                        <input type="text" class="form-control" id="name" placeholder="Enter your name">
                    </div>
                </div>
                <div class="form-group row">
                    <label for="email" class="col-sm-2 col-form-label">Email</label>
                    <div class="col-sm-10">
                        <input type="email" class="form-control" id="email" placeholder="Enter your email">
                    </div>
                </div>
                <div class="form-group row">
                    <label for="password" class="col-sm-2 col-form-label">Password</label>
                    <div class="col-sm-10">
                        <input type="password" class="form-control" id="password" placeholder="Enter your password">
                    </div>
                </div>
                <div class="row">
                    <div class="col-sm-10 offset-sm-2 mb-5">
                        <button type="submit" class="btn btn-primary">Sign Up</button>
                    </div>
                </div>
            </form>
        </div>
    </div>
</template>

<style>
.signup h1{
    align-items: center;    
}
.signup-form {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #3b1a88f8;
    color: #f0ffff;
    font-size: 25px;
    font-weight: bolder;
    margin: 5px;
    padding: 50px;
}
</style>