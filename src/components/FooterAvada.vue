<template>
<div class="container-fluid">
    <div class="container d-flex justify-content-between">
        <div class="">
            <div class="title">
                <h4>
                    Grow Your Online Business Strategically, and Improve Customer Retention.
                </h4>
            </div>
            <div class="logosm">
                <ul class=" d-flex">
                    <li class="icons"><font-awesome-icon icon="fa-brands fa-facebook-f"/></li>
                    <li class="icons"><font-awesome-icon icon="fa-brands fa-twitter" /></li>
                    <li class="icons"><font-awesome-icon icon="fa-brands fa-instagram" /></li>
                    <li class="icons"><font-awesome-icon icon="fa-brands fa-youtube" /></li>
                    <li class="icons"><font-awesome-icon icon="fa-brands fa-linkedin" /></li>
                    <li class="icons"><font-awesome-icon icon="fa-brands fa-tiktok" /></li>
                </ul>
                <p class="p1">© 2020 • Avada Consultant • Powered by WordPress</p>
            </div>
        </div>
        <div>
            <h6>Service</h6>
            <ul>
                <li v-for="(link, index) in service" :key="index" class="list_active"><a :href="link.href">{{ link.text }}</a></li>
            </ul>
            <p>Call Us (555) 802-1234</p>
        </div>
        <div>
            <h6>Resources</h6>
            <ul>
                <li v-for="(link, index) in resources" :key="index" class="list_active"><a :href="link.href">{{ link.text }}</a></li>
            </ul>
        </div>
        <div>
            <h6>Company</h6>
            <ul>
                <li v-for="(link, index) in company" :key="index" class="list_active"><a :href="link.href">{{ link.text }}</a></li>
            </ul>
            <p class="p2">info@yourcompany.com</p>
        </div>
    </div>
    <div class="icon"></div>
</div>

</template>

<script>
export default {
    name: "HeaderAvada",
        data() {
            return {
                service: [
                {
                    href: "#",
                    text: "Marketing Plan",
                },
                {
                    href: "#",
                    text: "Sales Development ˅",
                },
                {
                    href: "#",
                    text: "Digital Marketing",
                },
                {
                    href: "#",
                    text: "Pricing",
                },
                {
                    href: "#",
                    text: "Why Us",
                },
                {
                    href: "#",
                    text: "Case Studies",
                },
            ],
            resources: [
                {
                    href: "#",
                    text: "Learning Center",
                },
                {
                    href: "#",
                    text: "Video Tutorials",
                },
                {
                    href: "#",
                    text: "Customers",
                },
                {
                    href: "#",
                    text: "Blog",
                },
            ],
            company: [
                {
                    href: "#",
                    text: "Who We Are",
                },
                {
                    href: "#",
                    text: "Contact Us",
                },
                {
                    href: "#",
                    text: "Careers",
                },
            ]
        };
    },
};
</script>

<style lang="scss" scoped>
.container {
    margin-top: 5em;
}

.title {
    width: 400px;
}

ul{
    margin: 0px 0px 100px -34px;
}

li {
    display: flex;
    margin: 0px 0px 15px 0px
}

a{
    text-decoration:none;
    color:rgb(63, 61, 61);
    font-size: x-small;
}

p {
    font-size: x-small;
}

.p1{
    margin-top: 200px;
}

.p2{
    margin-top: 207px;
}

.icons{
    margin:17px 17px 0 0px;
}

.icon{
    margin: 1% 0% 1% 95%;
    background-color: orangered;
    width: 50px;
    height: 50px;
    border-radius: 50px;
    margin-right: 5px;
}
</style>
