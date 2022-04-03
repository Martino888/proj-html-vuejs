<template>
    <div class="container">
        <h1 class="title">
            Trusted by Leading Organisations
        </h1>
        <div class="d-flex justify-content-between">
            <div>
                <img src="@/assets/images/case-studies-1-1200x1349.jpg" alt="">
                <h4> How Spacesattrached five million visitors by improving the content </h4>
                <h1>200%</h1>
                <p>Higher revenue from digital </p>
                </div>
            <div>
                <img src="@/assets/images/case-studies-4-1200x1349.jpg" alt="">
                <h4>Creativity helped <br> Hemisferio to increase their breand reach vertically </h4>
                <h1>10x</h1>
                <p>Sales increase with the same ad spend </p>
            </div>
                <div>
                <img src="@/assets/images/case-studies-6-1200x1349.jpg" alt="">
                <h4> How  DigitalBox used Al-powered data insight to boost sales</h4>
                <h1>3-year</h1>
                <p>Higher revenue from digital </p>
            </div>
        </div>
        <div class="position">
            <button class="btn">Read More Case Studies</button>
        </div>

    </div>
</template>

<script>
export default {

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
    width: 350px;
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
