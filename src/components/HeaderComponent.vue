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

    <header>

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
                <a href="#">
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

</template>

<style lang="scss" scoped>

*{
    margin: 0 auto;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
    // selezonno qualunque cose che non sia un ul
    &:not(ul){
        padding:0;
    }
}

header{
    display: flex;
    justify-content: space-between;
    align-items: center;

    ul{
        display:flex;
        list-style: none;
    }

        li{
            a{
                display: inline-block;
                padding: 15px;
                color:grey;
                text-decoration: none;
                font-size: 1rem;
                font-weight: bold;


          }
       }
}


</style>