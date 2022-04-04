<template>
    <div class="container-fluid">
        <div class="container d-flex justify-content-between">
            <div class="title">
                <h1>Marketing Resources: Insider Advice on How to Increase Online Sales</h1>
            </div>
            <div>
                <button class="btn">Exsplore All Resources</button>
            </div>
        </div>
        <div class="container d-flex justify-content-between">
                <div>
                    <img src="@/assets/images/blog-posts-6.jpg" alt="">
                    <h4>Marketing Tips And Tricks For Your Website</h4>
                </div>
                <div>
                    <img src="@/assets/images/blog-posts-5.jpg" alt="">
                    <h4>How to Write Stunning Blog Post Titles</h4>
                </div>
                <div>
                    <img src="@/assets/images/blog-posts-4.jpg" alt="">
                    <h4>Techniques to Reduce Facebook Ads Spend</h4>
                </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.container-fluid {
    background-image: linear-gradient(to top, rgb(241, 238, 238)  10%, #e3e4e2 90%),
}

.title{
    width:500px;
    margin: 100px 0px 40px 0px;
}

.btn{
    background-color:  #f26f28;
    color:white;
    padding-left: 25px;
    padding-right: 25px;
    margin: 210px 0px 0px 300px;
}

img {
    width: 350px;
}

h4{
    width: 350px;
    margin-top: 1em;
}

    form {
        width: 400px;
        height: 500px;
        border-radius: 15px;
        background-color: white;
        justify-items: center;
        display: grid;
        margin-top: 70px;
        box-shadow: 1px 1px 1px 1px #f5f3f3;
        margin-right: 30px;
        margin-left: 30px;
}

    .circle {
        width: 100px;
        height: 100px;
        border-radius: 50px;
        border-radius: 50px;
        margin-top: 20px;
    }

    h5{
        margin: 0;
    }

    .expert{
        color:gray;
    }

    .numform{
        color: #f76210;
    }

    .formbtn {
        min-width: 350px;
        height:40px;
        background-color: #f76210;
        color: white;
        border-radius: 10px;
        border:none;
    }
    input{
        width: 350px;
        height: 45px;
        border-radius: 10px;
    }

    .submit{
        color:grey;
        font-size: x-small;
    }

    .square{
        margin: 5px;
        display:flex;
        flex-direction: column;
        height: 70px;
        width: 80px;
        background: #f5f3f3;
        border-radius: 7px;
        font-size: x-small;
        justify-content: end;
    }
</style>
