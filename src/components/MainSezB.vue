<template>
    <div class="container">
        <h1 class="title">
            Trusted by Leading Organisations
        </h1>
        <div class="d-flex justify-content-between">
            <div v-for="element in arrImg" :key="element.id">
                <img :src="element.img" alt="">
                <h4>{{element.title}}</h4>
                <h1>{{element.num}}</h1>
                <p>{{element.description}}</p>
            </div>
        </div>
        <div class="position">
            <button class="btn">Read More Case Studies</button>
        </div>

    </div>
</template>

<script>
import img1 from "@/assets/images/case-studies-1-1200x1349.jpg"
import img2  from "@/assets/images/case-studies-4-1200x1349.jpg"
import img3 from "@/assets/images/case-studies-6-1200x1349.jpg"
export default {
    name: "MainSezB",
        data () {
            return {
                arrImg:[
                    {
                        id: 1,
                        img:img1,
                        title:'How Spacesattrached five million visitors by improving the content',
                        num:'200%',
                        description:'Higher revenue from digital',
                    },
                    {
                        id: 1,
                        img:img2,
                        title:`Creativity helped Hemisferio to increase their breand reach vertically `,
                        num:'10x',
                        description:'Sales increase with the same ad spend',
                    },
                    {
                        id: 1,
                        img:img3,
                        title:'How  DigitalBox used Al-powered data insight to boost sales',
                        num: '3-year',
                        description:'Higher revenue from digital',
                    }
                ]
            }
        }

}
</script>

<style lang="scss" scoped>
.title {
    display: grid;
    justify-content: center;
    margin:3em 0 2em 0 ;
}

img {
    width: 350px;
}

h4{
    width: 330px;
    margin-top:15px;
}

h1{
    margin:20px 0 0 0;
}

p{
    font-size: x-small;

}

.position {
    display: grid;
    justify-content: center;
    margin:3em 0 2em 0 ;
}

.btn{
    background-color:  #f26f28;
    color:white;
    padding: 5px;
    padding-left: 30px;
    padding-right: 30px;
}

</style>
