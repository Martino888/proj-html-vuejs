<template>
    <div class="container d-flex justify-content-centre">
        <div>
            <img class="boximg" :src="object.img" alt="">
        </div>
        <div>
            <h3>{{ object.description }}</h3>
            <h5>{{ object.name }}</h5>
            <p>{{ object.position}}</p>
        </div>
    </div>
</template>

<script>
import img from "@/assets/images/large-testimonial-1200x1166.jpg"
export default {
    name: "MainSezD",
        data () {
            return {
                object:{
                    img:img,
                    description:`“The team at Avada Marketing Consultant is fabulous.
                                They helped us unlock our potential online and offline.
                                We have experienced year on year growth due to
                                their progressive approach.”`,
                    name: 'Kate Schadler',
                    position:'Marketing Consultant - Abstract'
                }
            }
        }

}
</script>

<style lang="scss" scoped>


.boximg{
    width: 550px;
    height: 500px;
    border-radius: 10px;
    margin: 80px 0px 80px 30px;

}

h3{
    width: 420px;
    margin: 140px 0px 0px 100px;
}

h5{
    margin: 40px 0px 0px 100px;
}

p{
    font-size: x-small;
    margin: 0px 0px 0px 100px;
}

</style>
