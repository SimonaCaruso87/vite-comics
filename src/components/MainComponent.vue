<script>
export default{
    name: "MainComponent",
    data(){
        return{

        }
    },
    methods:{

    }
}
</script>

<template>

    <main>
        <div class="container container-main">
            <div>
                <img src="src/assets/img/buy-comics-digital-comics.png" alt="">
            </div>
            <div>
                DIGITAL COMICS
            </div>    
            <div>
                <img src="src/assets/img/buy-comics-merchandise.png" alt="">
            </div>
            <div>
                DC MERCHANDISE 
            </div>
            <div>
                <img src="src/assets/img/buy-comics-subscriptions.png" alt="">
            </div>
            <div>
                SUBSCRIPTION
            </div>    
            <div>
                <img src="src/assets/img/buy-comics-shop-locator.png" alt="">
            </div>
            <div>
                COMIC SHOP LOCATOR
            </div>     
            <div>
                <img src="src/assets/img/buy-dc-power-visa.svg" alt="">
            </div>
            <div>
                DC POWER VISA
            </div>
        </div>
    </main>

    <section class="main-bottom">

    </section>

</template>

<style lang="scss" scoped>

main{
   background-color: #0282F9;
   
      img{
        width: 60px;
      }
      .container-main{
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 30px;
        font-size: 15px;
        color:white;
      }

      div{
        padding-left: 30px;
      }

}

.main-bottom{
    background-image: url("src/assets/img/footer-bg.jpg");
    height: 300px;
}


</style>