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

h5{
    width: 300px;
}


</style>
