<template>
    <div class="container-fluid">
        <div class="container d-flex justify-content-between">
            <div class="title">
                <h1 class="bold bottom">Let’s Make Things Happen</h1>
                <h5>Curabitur ac leo nunc. Vestibulum et mauris <br> vel ante finibus maximus nec ut leo. Integer consectetur.</h5>
                ________
                <p class="corsivo">“The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online and offline. We have experienced year on year growth due to their progressive approach.”</p>
                <h6 class="bold">George Anderson</h6>
                <p class="small">Digitalbox CEO</p>
            </div>
            <div>
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
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.container-fluid{
    background-color:black;
    height: 700px;
}
.title{
    width: 480px;
    color: white;
    margin: 100px 0 0 0;
}

.bottom{
    margin-bottom:1em;
}

.bold{
    font-weight: bold;
}

.corsivo{
    font-style: italic;
    margin-top:1em;
}

.small {
    font-size: x-small
}

    form {
        width: 400px;
        height: 500px;
        border-radius: 15px;
        background-color: white;
        justify-items: center;
        display: grid;
        margin-top: 90px;
        box-shadow: 1px 1px 1px 1px #f5f3f3;
        margin-right: 30px;
        margin-left: 30px;
}

    .circle {
        width: 70px;
        height: 70px;
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


</style>
