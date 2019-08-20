<template>
    <div id="app">
        <div id="header">
            <div id="left">
                <h1 id="name">Cody Chase</h1>
            </div>
            <div id="middle">
                <img src='../assets/logo_cropped.jpg' id="kplogo">
            </div>
            <div id="right">
                <h1>407.414.9770</h1>
            </div>
        </div>
    </div>

</template>

<script>


</script>

<style>
    #header{
        height: 100px;
        min-width: 1002px;
        width: 100%;
/*        background-color: pink;*/
        z-index: 2;
    }
    #kplogo{
        height: 90%;
        width: 100%;
        max-width: 250px;
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
    #left{
        width: 39%;
        height: 100%;
/*        background-color: blue;*/
        float: left;
        padding-right: 5px;
        padding-top: 10px;
    }
    #name{
        float: right;
    }
    #middle{
        width: 20%;
        height: 100%;
/*        background-color: green;*/
        float: left;
    }
    #right{
        width: 40%;
        height: 100%;
/*        background-color: purple;*/
        float: left;
        padding-left: 5px;
        padding-top: 10px;
    }

</style>