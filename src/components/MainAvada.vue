<template>
    <div class=" hero container-fluid">
        <div class="row col-5">
        <div class="title">
            <h1>
                Unlock Your Online <br> Growth Potential
            </h1>
            <p class="text-white">
                Online marketing to secure customer retention,<br>
                leads,and sales.We focus on the bigger picture.
            </p>
            <button class="btn">Our Services &#129122;</button>
        </div>
        </div>
        <form class="overflow-visible">
            <img class="circle" src="@/assets/images/marketing-consultant-expert.jpg" alt="">
            <h5>Richard Madsen</h5>
            <div class="expert">Marketing Consultant Expert</div>
            <div class="numform">📞 (555)802-1234</div>
            <input type="name" class="form-control" id="Inputname" placeholder="Your Name*">
            <input type="email" class="form-control" id="Inputname" placeholder="Your Email*">
            <input type="email" class="form-control" id="Inputname" placeholder="Your Phone Number*">
            <button type="submit" class=" formbtn">Get a callback</button>
            <div class="submit">By submitting my data I agree to be contacted</div>
        </form>
        <div>
            <div class="square">Demos</div>
            <div class="square">On saleq</div>
        </div>

    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .hero{
        display:flex;
        margin-top: 1em;
        background-repeat: no-repeat;
        background-size: 100%;
        height: 550px;
        justify-content: space-between;
        background-image: url(@/assets/images/marketing-intro.jpg);
        // background-image: linear-gradient(to right, rgb(0, 87, 128) 15%,rgb(236, 129, 14) 100%),
    }

    h1{
        color:white;
    }

    .btn{
        border:2px solid white;
        background-color:white;
        border-radius: 7px;
    }

    .btn:hover{
        color:white;
        background-color:transparent;
        border:solid 2px#f5f3f3;
    }

    .title{
        padding: 75px;
        margin-left: 65px;
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
