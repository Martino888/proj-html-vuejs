<template>
        <div class="container">
            <div class=" d-flex" >
                <div class="boxs">
                    <img src="@/assets/images/screen1.jpg">
                </div>
                <div class="boxs">
                    <div class="d-flex">
                        <div class="icon"></div>
                        <p> Business Growth </p>
                    </div>
                    <h1>Increrease Brand <br> Awareness</h1>
                    <p class="p">
                        Lorem ipsum dolor sit amet, consectetur<br>
                        adipiscing elit. Sed auctor placerat <br>
                        luctus. Nullam sit amet ante sed orci <br>
                        convallis gravida et at massa.
                    </p>
                    <button class="btn">Get a Consultation</button>
                </div>
            </div>
            <div class=" d-flex">
                <div class="boxs boxsex2">
                    <div class="d-flex">
                        <div class="icon2"></div>
                        <p> Investors In People</p>
                    </div>
                    <h1>In-House Sales <br> Training</h1>
                    <p class="p">
                        Lorem ipsum dolor sit amet,consectetur <br>
                        adipiscing elit. Sed auctor placerat luctus.<br>
                        Nullam sit amet ante sed orci convallis<br>
                        gravida et at massa.
                    </p>
                    <button class="btn">Get a Consultation</button>
                </div>
                <div class="boxs imgsez2">
                    <img  src="@/assets/images/screen2.jpg">
                </div>
            </div>
            <div class=" d-flex" >
                <div class="boxs">
                    <img src="@/assets/images/screen3.jpg">
                </div>
                <div class="boxs">
                    <div class="d-flex">
                        <div class="icon3"></div>
                        <p>Social Media Analysis </p>
                    </div>
                    <h1>Increrease Brand <br> Awareness</h1>
                    <p class="p">
                        Lorem ipsum dolor sit amet,<br>
                        consectetur adipiscing elit. Sed auctor <br>
                        placerat luctus. Nullam sit amet ante <br>
                        sed orci convallis gravida et at massa.
                    </p>
                    <button class="btn">Get a Consultation</button>
                </div>
            </div>
            <div class="titledown">
                <h1>Some Brands We Work Whith</h1>
                <p class="p2">Quisque aliquet, libero consequat elementum convallis.</p>
            </div>
            <div class="society">
                    <img class="imgsoc"  v-for="link in links" :key="link.img" :src="link.img" />
            </div>
            <div class="d-flex bag  d-flex justify-content-around align-items-center">
                <div class="d-flex">
                    <img class="circle" :src="object.img" alt="">
                    <div class="margin">
                        <h6>{{object.nome}}</h6>
                        <p class="font">{{object.position}}</p>
                    </div>
                </div>
                <div>
                    <h5>{{object.expert}}</h5>
                </div>
                <div>
                    <button class="btn">{{object.info}}</button>
                </div>
            </div>
        </div>
</template>

<script>
import society1 from"../assets/images/abstract.png"
import society2 from"@/assets/images/cglobal.png"
import society3 from"@/assets/images/next.png"
import society4 from"@/assets/images/hemisferio.png"
import society5 from"@/assets/images/spaces.png"
import society6 from"@/assets/images/digitalbox.png"
import imgx from "@/assets/images/marketing-expert-cta.png"
export default {
    data () {
        return {
            links:[
                {
                img:society1
            },
            {
                img: society2
            },
            {
                img:society3
            },
            {
                img:society4
            },
            {
                img:society5
            },
            {
                img:society6
            }
        ],
        object:{
            img:imgx,
            nome:'Sandy Reiff',
            position:'Marketing Consultant Expert',
            expert:'Drive leads and Sales whid Avada',
            info:'📞 (555)802-1234',
        }
        }
    }
}
</script>

<style lang="scss" scoped>

.bag{
    box-shadow: 0px 7px 18px 0px #dbd6d6;
    border-radius: 8px;
}

.container {
    margin-top:5em;
}

.boxs{
    width: 550px;
    margin: 0 24px 200px 24px;
}

.boxsex2{
    margin: 0 24px 50px 100px;
}

img{
    width: 500px;
}

.icon{
    background-color: blue;
    width: 30px;
    height: 30px;
    border-radius: 50px;
    margin-right: 5px;
}

.icon2{
    background-color: yellow;
    width: 30px;
    height: 30px;
    border-radius: 50px;
    margin-right: 5px;
}
.icon3{
    background-color: green;
    width: 30px;
    height: 30px;
    border-radius: 50px;
    margin-right: 5px;
}


.imgsez2{
    margin-left: -170px;
}

.p{
    width: 400px;
}

.btn{
    background-color: #f26f28;
    color:white;
    padding: 5px;
    padding-left: 30px;
    padding-right: 30px;
}

.btn:hover {
    background-color:#f76210;
    }

.titledown{
    display: grid;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
}

.p2{
    justify-self: center;
}

.society {
    display: flex;
    justify-content: space-between;
    margin:2em 0 7em 0;

}

.imgsoc{
    width: 120px;
}

.font{
    font-size:x-small
}

.circle {
    width: 50px;
    height: 50px;
    border-radius: 50px;
    border-radius: 50px;
    margin-top:15px;
}

.margin{
    padding: 20px 0px 0px 15px;
}

h6{
    margin-bottom: 0;
}
</style>
