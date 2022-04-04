<template>
    <div class="container">
        <div class="title">
            <h4>Grow Your Online Business Strategically, and Improve Customer Retention.</h4>
        </div>
        <div class="logosm">
            <ul class="icons">
                    <li><i class="fa-brands fa-facebook-f"></i></li>
                    <li><i class="fa-brands fa-twitter"></i></li>
                    <li><i class="fa-brands fa-youtube"></i></li>
                    <li><i class="fa-brands fa-instagram"></i></li>
                </ul>
        </div>
    </div>
</template>

<script>
export default {
    name:'HeaderAvada',
    data () {
        return {
            links:[
                {
                href: '#',
                text: 'Home ˅'
            },
            {
                href: '#',
                text: 'Service ˅'
            },
            {
                href: '#',
                text: 'Why Us'
            },
            {
                href: '#',
                text: 'Case Sudies'
            },
            {
                href: '#',
                text: 'About'
            },
            {
                href: '#',
                text: 'Blog'
            },
            {
                href: '#',
                text: '📞 (555)802-1234'
            }
            ]
        }
    }

}
</script>

<style lang="scss" scoped>

.container {
    margin-top: 5em;
}

.title {
    width: 400px;
}

</style>
