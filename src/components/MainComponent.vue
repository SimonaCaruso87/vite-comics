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
    <!-- Main Top -->
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
                <h4>
                    DC MERCHANDISE    
                </h4>
            </div>
            <div>
                <img src="src/assets/img/buy-comics-subscriptions.png" alt="">
            </div>
            <div>
                <h4>
                    SUBSCRIPTION
                </h4>
            </div>    
            <div>
                <img src="src/assets/img/buy-comics-shop-locator.png" alt="">
            </div>
            <div>
                <h4>
                    COMIC SHOP LOCATOR
                </h4>
            </div>     
            <div>
                <img src="src/assets/img/buy-dc-power-visa.svg" alt="">
            </div>
            <div>
                <h4>
                    DC POWER VISA
                </h4>
            </div>
        </div>
    </main>

    <!-- Main Bottom -->
    <section>
        <div class="debug">
            <!-- Container-Left -->
            <div class="container-left" >
                <div class="container-section">
                    <div class="text-main-bottom">
                        DC COMICS
                    </div>
                    <div>
                        <ul>
                            <li>
                                <a href="#">
                                    Characters
                                </a>
                            </li>
                        </ul>
                        <ul>
                            <li>
                                <a href="#">
                                    Comics
                                </a>
                            </li>
                        </ul>
                        <ul>
                            <li>
                                <a href="#">
                                    Movies
                                </a>
                            </li>
                        </ul>
                        <ul>
                            <li>
                                <a href="#">
                                    Tv
                                </a>
                            </li>
                        </ul>
                        <ul>
                            <li>
                                <a href="#">
                                    Games
                                </a>
                            </li>
                        </ul>
                        <ul>
                            <li>
                                <a href="#">
                                    Video
                                </a>
                            </li>
                        </ul>
                        <ul>
                            <li>
                                <a href="#">
                                    News
                                </a>
                            </li>
                        </ul>
                </div>
                
                <div class="text-main-bottom">
                    SHOP
                </div>
                <div>
                    <ul>
                        <li>
                            <a href="#">
                                Shop DC
                            </a>
                        </li>
                    </ul>
                    <ul>
                        <li>
                            <a href="#">
                                Shop DC Collectibles
                            </a>
                        </li>
                    </ul>

                </div>    

            </div>
             
            <div>
                <div class="text-main-bottom-link" >
                    <h4>
                        DC
                    </h4>
                    <ul>
                        <li>
                            <a href="#">
                               Terms of use
                            </a>
                        </li>
                        <li>
                            <a href="#">
                               Privacy Police(new)
                            </a>
                        </li>
                        <li>
                            <a href="#">
                               Ad Choises
                            </a>
                        </li>
                        <li>
                            <a href="#">
                               Adversiting
                            </a>
                        </li>
                        <li>
                            <a href="#">
                               Jobs
                            </a>
                        </li>
                        <li>
                            <a href="#">
                               Subscriptions
                            </a>
                        </li>
                        <li>
                            <a href="#">
                               Talent workshops
                            </a>
                        </li>
                        <li>
                            <a href="#">
                               CPSC Certificates
                            </a>
                        </li>
                        <li>
                            <a href="#">
                               Ratigs
                            </a>
                        </li>
                        <li>
                            <a href="#">
                               Shop Help
                            </a>
                        </li>
                        
                    </ul>

                </div>
                
            </div>
            
            <div>
                <h4>
                    SITES
                </h4>
                <ul>
                    <li>
                        <a href="">
                           DC
                        </a>
                    </li>
                    <li>
                        <a href="">
                          MAD Magazine                      
                        </a>
                    </li>
                    <li>
                        <a href="">
                         DC Kids
                        </a>
                    </li>
                    <li>
                        <a href="">
                        DC Universe
                        </a>
                    </li>
                    <li>
                        <a href="">
                           DC Powervisa
                        </a>
                    </li>
                </ul>
            </div>
            </div>
            <!-- Container-right -->
            <div class="logo">
                <img src="src/assets/img/dc-logo-bg.png" alt="">
            </div>

        </div>



    </section>

</template>

<style lang="scss" scoped>


main{
   background-color: #0282F9;
   height: 150px;
   
      img{
        width: 60px;
      }
      .container-main{
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 30px;
        font-size: 15px;
 ;       color:white;
      }

      div{
        padding-left: 30px;
      }

}

section{


    background-image: url("src/assets/img/footer-bg.jpg");
    background-repeat:no-repeat;
    background-size: cover;
    height:calc(100vh - 550px);
    .debug{
        border: 3px solid yellow;
        display:flex;
        .logo{
            width:100%;
        }

        .container-left{
            display:flex;
        }
    }

    .container-section{
            max-width:1400px;
            margin:0 auto;
            justify-content:space-between;

            .text-main-bottom{
            color:white;
            font-weight: bolder;
            font-size: 23px;
            text-decoration: none;
            padding-top: 20px;
            padding-bottom: 10px;
          }

    }

    .text-main-bottom-link{
            color:white;
            font-weight: bolder;
            font-size: 23px;
            text-decoration: none;
            padding-top: 20px;
            padding-bottom: 10px;
          }
                
    ul{
        list-style: none;
        padding-left: 0;

        li{
            a{
                display: inline-block;
                padding-top: 10px;
                color:#546C7B;
                text-decoration: none;
                font-size: 1rem;

          }
       }        
    }


}


</style>