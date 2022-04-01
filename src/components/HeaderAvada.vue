<template>
  <div>
    <header>
        <div class="contain">
            <img class="logo" src="@/assets/images/avada-marketing-logo.png" alt="logo">
            <ul>
                <li v-for="(link, index) in links" :key="index" class="list_active"><a :href="link.href">{{link.text}}</a></li>
            </ul>
            <button class="btn"> Free Quote</button>
        </div>
    </header>
  </div>
</template>

<script>
/* eslint-disable */
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
  .header {
      height: 70px;
  }

  .contain{
    display:flex;
    align-items:center;
    justify-content: center;
    background-color: white;
    width: 100%;
  }

    ul{
      margin-bottom: 0rem;
  }
    li{
      display:inline-block;
      padding: 15px;
    }

    a{
      text-decoration:none;
      color:rgb(63, 61, 61);
      font-size: x-small;
    }

    a:hover{
      color:rgb(255, 123, 0);
    }

    .here{
      width: 100%;
      background-color: black;
      color:white;
    }

    .list_active:hover {
      color: rgb(255, 111, 0);
      &::after {
      content: "";
        display: block;
        width: 30px;
        height: 2px;
        background-color: rgb(255, 123, 0);
        margin: auto;
        margin-top: 1rem;
        margin-bottom: -36px;
      }}

    .btn{
      background-color: rgba($color: #f26f28, $alpha: 0.3);
      color:#f76210;
      padding: 5px;
      padding-left: 30px;
      padding-right: 30px;
    }

    .btn:hover {
      background-color:#f76210;
    }

</style>
