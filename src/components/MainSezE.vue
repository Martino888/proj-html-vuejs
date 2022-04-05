<template>
    <div class="container-fluid">
        <div class="container d-flex justify-content-between">
            <div class="title">
                <h1>{{object.title}}</h1>
            </div>
            <div>
                <button class="btn">{{object.button}}</button>
            </div>
        </div>
        <div class="container d-flex justify-content-between">
            <div v-for="(element,index) in arrCards" :key="index.id" >
                <img :src="element.img" alt="">
                <h4>{{element.description}}</h4>
            </div>
        </div>
    </div>
</template>

<script>
import blog6 from "@/assets/images/blog-posts-6.jpg"
import blog5 from "@/assets/images/blog-posts-5.jpg"
import blog4 from "@/assets/images/blog-posts-4.jpg"
export default {
    name:'MainSezE',
        data () {
            return {
                object: {
                    title: 'Marketing Resources: Insider Advice on How to Increase Online Sales',
                    button:'Exsplore All Resources',
                },
                arrCards: [
                {
                    id: '1',
                    img: blog6,
                    description:'Marketing Tips And Tricks For Your Website',
                },
                {
                    id: '2',
                    img: blog5,
                    description:'How to Write Stunning Blog Post Titles',
                },
                {
                    id: '3',
                    img: blog4,
                    description:'Techniques to Reduce Facebook Ads Spend',
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
.container-fluid {
    background-image: linear-gradient(to top, rgb(241, 238, 238)  10%, #e3e4e2 90%);
    height:750px;
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

</style>
