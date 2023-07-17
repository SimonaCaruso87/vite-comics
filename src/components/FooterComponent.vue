<script>
export default{
    name: "FooterComponent",
    data(){
        return{

        }
    },
    methods:{

    }
}
</script>

<template>

    <footer>
        <div class="container">
            <div class="footer-cols">
                <div class="font-footer">
                    <h3>
                        SIGN-UP NOW
                    </h3>
                </div>

                <div class="footer-cols-icon">
                    <h3>
                        FOLLOW US
                    </h3>
                    <div>
                        <img src="src/assets/img/footer-facebook.png" alt="">
                    </div>
                    <div>
                        <img src="src/assets/img/footer-periscope.png" alt="">
                    </div>
                    <div>
                        <img src="src/assets/img/footer-pinterest.png" alt="">
                    </div>
                    <div>
                        <img src="src/assets/img/footer-twitter.png" alt="">
                    </div>
                    <div>
                        <img src="src/assets/img/footer-youtube.png" alt="">
                    </div>
                </div>
            </div>
          
        

        </div>
    </footer>

</template>

<style lang="scss" scoped>

footer{

    padding:40px;
    text-align: center;
    background-color:#303030;
    height: 140px;

    .footer-cols{
        display: flex;
        justify-content: space-between;

        .font-footer {
            border:1px solid #0482F9;
            color: white;
            padding:15px;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;

        .footer-cols-icon{
            display: flex;
            

        }

            img{
        height:40px;

        }
    }
        }




}

</style>