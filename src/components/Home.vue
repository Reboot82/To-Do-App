<template>
    <div class="row">
        <div id="home" class="col-sm-12 text-center">
            <div class="background">
                <h1>Much To-Do About Nothing</h1>
                <h2>Your personal organization app</h2>
                <h5>username:</h5>
                <h5>password:</h5>
                <button class="btn btn-success">Sign In</button>
                <button class="btn btn-success">Sign Up</button>
            </div>
        </div>
    </div>
</template>

<style>
    #home {
        background: url("../../src/assets/background.jpg");
        background-size: cover;
        height: 800px;
        padding: 10%;
    }

    h1, h2 {
        margin: 6%;
    }

    .background {
        background: rgb(122, 122, 122);
        opacity: 0.8;
        max-width: 60%;
        margin: 0 auto;
        padding: 20px 0;
    }
</style>