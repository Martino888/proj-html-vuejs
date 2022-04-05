<template>
    <div class="container-fluid">
        <div class="container">
            <div class="d-flex justify-content-between">
                <div class="box">
                    <h1>{{object.title}}</h1>
                    <p>{{object.paragraph}}</p>
                    <buttonq class="btn"> {{object.button}} </buttonq>
                </div>
                <div>
                    <img class="boximg" :src="object.img" alt="">
                </div>
            </div>
        </div>
        <div class="container d-flex justify-content-between">
            <div class="box">
                <h4>{{object2.title}}</h4>
                <p>{{object2.paragraph}}</p>
                <br>
                <h4>{{object2.title2}}</h4>
                <p>{{object2.paragraph2}}</p>
            </div>
            <div class="squar">
                <div class="d-flex">
                    <div class="circle">
                        <!-- <i class="bi bi-layout-sidebar"></i> -->
                    </div>
                    <div>
                        <h4>Accountability</h4>
                        <p>Curabitur ac leo nunc vestibulum</p>
                    </div>
                </div>
                    <div class="d-flex">
                    <div class="circle">
                        <!-- <i class="bi bi-layout-sidebar"></i> -->
                    </div>
                    <div>
                        <h4>Transparency</h4>
                        <p>Curabitur ac leo nunc vestibulum</p>
                    </div>
                </div>
                    <div class="d-flex">
                    <div class="circle">
                        <!-- <i class="bi bi-layout-sidebar"></i> -->
                    </div>
                    <div>
                        <h4>Investment</h4>
                        <p>Curabitur ac leo nunc vestibulum</p>
                    </div>
                </div>
            </div>
        </div>
        <h3 class="title">
            Awards
        </h3>

        <!-- <div class="society">
            <img class="imgsoc"  v-for="link in links" :key="link.img" :src="link.img" />
        </div> -->

        <div class="society ">
            <div class="align">
                <img class="imgsoc" src="@/assets/images/award-a.png" alt="logo society">
                    <p class="bottom">Winner Seo Master MAGT</p>
                    <p class="bottom">Smart Start Award 2017</p>
            </div>
            <div class="align">
                <img class="imgsoc" src="@/assets/images/award-b.png" alt="logo society">
                <p class="bottom">Top Social Media Agencies</p>
                <p class="bottom" >Next Partner 2018</p>
            </div>
            <div class="align">
                <img class="imgsoc" src="@/assets/images/award-c.png" alt="logo society ">
                <p class="bottom">10 Fastest Growing Abstract</p>
                <p class="bottom">Solution Providers 2019</p>
            </div>
            <div class="align">
                <img class="imgsoc" src="@/assets/images/award-d.png" alt="logo society">
                <p class="bottom">National Excellence Agencie</p>
                <p class="bottom">Award Winner 2020</p>
            </div>
        </div>
    </div>
</template>

<script>
import img from "@/assets/images/we-boost-our-clients-800x732.jpg"
// import img1 from "@/assets/images/award-a.png"
// import img2 from "@/assets/images/award-b.png"
// import img3 from "@/assets/images/award-c.png"
// import img4 from "@/assets/images/award-d.png"

export default {
    name: "MainSezC",
    data () {
        return {
            object: {
                title: "We Boost Our Clients' Bottom Line by Optimizing Their Growth Potenzial.",
                paragraph:'Quisque aliquet, libero consequat elementum convallis, erat risus imperdiet pellentesque sem neque eget.',
                button:'Why Work With Us',
                img:img
            },
            object2:{
                title: 'We Build Relationships',
                paragraph: "Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur",
                title2: 'Proprietary Processes',
                paragraph2:"Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur",
            },
        }
    }
}
</script>

<style lang="scss" scoped>

.container-fluid {
    height:1400px ;
    background-image: linear-gradient(to top, rgb(241, 238, 238)  10%, #e3e4e2 90%);
}

.box{
    width: 420px;
    margin: 120px 0px 0px 50px;
}

.btn{
    background-color:  #f26f28;
    color:white;
    padding: 5px;
    padding-left: 25px;
    padding-right: 25px;
}

.boximg{
    width: 550px;
    height: 450px;
    border-radius: 8px;
    margin: 80px 0px 0px 0;
}

.circle{
    margin: 0px 11px 30px 0px;
    height: 72px;
    width: 72px;
    line-height: 72px;
    border-radius: 20px;
    border: 2px solid orangered
}

.squar {
    margin: 120px 160px 0 0px ;
}

.title {
    display: grid;
    justify-content: center;
    margin:2em 0 2em 0 ;
}

.society {
    display: flex;
    justify-content: space-evenly;
    margin:2em 0 0 0;
}

.imgsoc{
    width: 120px;
}

.align{
    display: block;
    text-align:center
}

.bottom{
    margin-bottom: 0;
}

</style>
