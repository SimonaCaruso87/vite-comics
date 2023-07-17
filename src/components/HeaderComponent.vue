<script>
export default{
    name: "HeaderComponent",
    data(){
        return{

        }
    },
    methods:{

    }
}
</script>

<template>

    <header class="container" >

        <div class="logo">
        <img src="src/assets/img/dc-logo.png" alt="Logo">
        </div>

        <ul>
            <li>
                <a href="#">
                    CHARACTERS
                </a>
            </li> 
            <li>
                <a href="#" class="active">
                    COMICS
                </a>
            </li> 
            <li>
                <a href="#">
                    MOVIES
                </a>
            </li> 
            <li>
                <a href="#">
                    TV
                </a>
            </li> 
            <li>
                <a href="#">
                    GAMES
                </a>
            </li> 
            <li>
                <a href="#">
                    COLLECTIBLES
                </a>
            </li> 
            <li>
                <a href="#">
                    VIDEOS
                </a>
            </li> 
            <li>
                <a href="#">
                    FANS
                </a>
            </li> 
            <li>
                <a href="#">
                    NEWS
                </a>
            </li> 
            <li>
                <a href="#">
                    SHOP
                </a>
            </li> 
        </ul>
            
    </header>

    <section class="header-bottom">
        <div class="container">
            &rarr; Content goes here &larr;
        </div>
    </section>

</template>

<style lang="scss" scoped>


header{
    display: flex;
    justify-content: space-between;
    align-items: center;

    .logo{
        padding: 10px;
    }

    ul{
        display:flex;
        list-style: none;

        li{
            a{
                display: inline-block;
                padding: 15px;
                color:grey;
                text-decoration: none;
                font-size: 1rem;
                font-weight: bold;

                &.active {
                    color:#0282F9;
                    text-decoration: underline;
                }
            

          }
       }        
    }


}

.header-bottom{
    padding:40px;
    background-color: black;
    margin: 0 auto;
    color: white;
    font-size: 2rem;
}


</style>