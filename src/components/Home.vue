<template>
  <div class="home">
    <header class="desktop">
      <input class="bg-white focus:outline-none focus:shadow-outline border border-gray-300 rounded-lg py-2 px-4 block w-full appearance-none leading-normal" type="email" placeholder="jane@example.com">


        <div class="ui middle aligned grid">
           <div class="eight wide column">
                <a href="/" class="logo tw-mt-10px mt-0"><img src="/src/assets/images/gleac-logo.png"></a>
           </div>

          <div class="eight wide right aligned column">
              <div class="menu">
                <a class="item">Our Whitepaper</a>
                <a class="item">About Us</a>
                <a class="item">Take Benchmark</a>
                <button class="ui button">
                  Login
                </button>
              </div>
          </div>

        </div>

    </header>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">
   .home{
     header{
       padding: 18px 30px;
       background-color: #fff;
       a.logo{
         max-width: 110px;
         display: inline-block;
         img{
           width: 100%;
         }
       }
       .menu a{
         font-size: 12px;
         color: #0065ad;
         font-weight: 600 ;
         margin-right: 12px;
       }
     }
   }

</style>
