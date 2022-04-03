<template>
        <div class="container">
            <div class="x d-flex" >
                <div class="boxs">
                    <img src="@/assets/images/screen1.jpg">
                </div>
                <div class="boxs">
                    <p> O Business Growth </p>
                    <h1>Increrease Brand <br> Awareness</h1>
                    <p class="p">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Dolores non quia omnis error maxime dolorem ea deleniti,
                        impedit et vero facere.
                        Tenetur saepe incidunt earum non ipsam! Corrupti,
                        quis nihil?
                    </p>
                    <button class="btn">Get a Consultation</button>
                </div>
            </div>
            <div class="x d-flex">
                <div class="boxs boxsex2">
                    <p class=""> O Business Growth </p>
                    <h1>In-House Sales <br> Training</h1>
                    <p class="p">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Dolores non quia omnis error maxime dolorem ea deleniti,
                        impedit et vero facere.
                        Tenetur saepe incidunt earum non ipsam! Corrupti,
                        quis nihil?
                    </p>
                    <button class="btn">Get a Consultation</button>
                </div>
                <div class="boxs imgsez2">
                    <img  src="@/assets/images/screen2.jpg">
                </div>
            </div>
            <div class="x d-flex" >
                <div class="boxs">
                    <img src="@/assets/images/screen3.jpg">
                </div>
                <div class="boxs">
                    <p class=""> O Business Growth </p>
                    <h1>Increrease Brand <br> Awareness</h1>
                    <p class="p">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Dolores non quia omnis error maxime dolorem ea deleniti,
                        impedit et vero facere.
                        Tenetur saepe incidunt earum non ipsam! Corrupti,
                        quis nihil?
                    </p>
                    <button class="btn">Get a Consultation</button>
                </div>
            </div>
            <div class="titledown">
                <h1>Some Brands We Work Whith</h1>
                <p class="p2">Quisque aliquet, libero consequat elementum convallis.</p>
            </div>
            <div class="society">
                <img class="imgsoc" src="@/assets/images/abstract.png" alt="logo society">
                <img class="imgsoc" src="@/assets/images/cglobal.png" alt="logo society">
                <img class="imgsoc" src="@/assets/images/next.png" alt="logo society ">
                <img class="imgsoc" src="@/assets/images/hemisferio.png" alt="logo society">
                <img class="imgsoc" src="@/assets/images/spaces.png" alt="logo society">
                <img class="imgsoc" src="@/assets/images/digitalbox.png" alt="logo society">
            </div>
            <div class="d-flex bag">
                <div class="d-flex">
                    <img class="circle" src="@/assets/images/marketing-consultant-expert.jpg" alt="">
                    <h6>Sandy Reiff</h6>
                    <p class="font">Marketing Consultant Expert</p>
                </div>
                <div>
                    <h5>Drive leads and Sales whid Avada</h5>
                </div>
                <div>
                    <button class="btn">📞 (555)802-1234</button>
                </div>
            </div>

        </div>
</template>

<script>
export default {
    data () {
        return {
            links:[
                {
                img:"@/assets/images/abstract.jpg"
            },
            {
                img: "@/assets/images/cglobal.png"
            },
            {
                img:"@/assets/images/next.png"
            },
            {
                img:"@/assets/images/hemisferio.png"
            },
            {
                img:"@/assets/images/spaces.png"
            },
            {
                img:"@/assets/images/digitalbox.png"
            }
        ]
        }
    }
}
</script>

<style lang="scss" scoped>

.bag{
    border: 1px solid black;
    box-shadow: 1px 1px 1px 1px #f5f3f3;
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

.imgsez2{
    margin-left: -170px;
}

.p{
    width: 400px;
}

.btn{
    min-width: 200px;
    height:50px;
    background-color: #f76210;
    color: white;
    border-radius: 10px;
    border:none;
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
    margin:2em 0 7em 0
}

.imgsoc{
    width: 100px;
}

.font{
    font-size:x-small
}

.circle {
        width: 50px;
        height: 50px;
        border-radius: 50px;
        border-radius: 50px;
    }
</style>
