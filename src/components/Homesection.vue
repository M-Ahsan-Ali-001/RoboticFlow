<script setup lang="ts"> 

const vm:any=()=>{
    alert("tets")
}

</script>
<template>
    <div class="home-section">
        <div class="box-area">
            <div class="start-box"  >
                <div class="arrowNEw">
                    <img src="../assets/arrow1.png" alt="arrow" class="arrow" />
                </div>

                <div class="text-box" @click="vm" >
                    Start Now
                </div>


                <div class="arrowNEw">
                    <img src="../assets/arrow1.png" alt="arrow" class="arrow" />
                </div>
                

            </div>

            <div class="second-box">
                <div class="hold-text-boxx2">
                    <p class="head-text-box2">
                    Transforming
                    Business
                    Operations
                </p>

                <p class="sub-text-box2">
                    Daplit is a product that enables the
                    </p> 
                    <p class="highlith">
                        automation of business processes using the 
                    
                        tools and systems

                </p>

                <p class="sub-text-box2">
                    that your company already has.
                    </p>
                </div>


        


                <div class="card-holder">
                    <div class="card1">
                        <div class="percent">
                            90%
                        </div>

                        <div class="cd-btm-txt">
                            Increase <br/>In Produtivity
                        </div>
                    </div>
                    <div class="card1">

                        <div class="percent">
                            42%
                        </div>

                        <div class="cd-btm-txt">
                            Cost <br/>Savings
                        </div>
                    </div>

                </div>

</div>








        </div>



        <div class="video-area">
            <div class="black-sheet">

                <div class="little-card">
                    <div class="circle"> </div>

                    <div class="circle c2"></div>
                    <div class="circle c3"></div>
                    <div class="circle c4">+</div>


                    <div class="little-card-text">
                        Thousand of <br/>
                        Companies use Daplit
                    </div>

                </div>


                <div class="little-crd-btn-holder">
                    <div class="button-video">Watch A Demo</div>
                <div class="image-arrow">
                    <img src="../assets/arrow.png"/>
                </div>
                </div>
            </div>

            <video id="video-box" height="100%" width="100%" autoplay muted loop>
                <source src="../assets/video/video.mp4" type="video/mp4" >
            </video>
        </div>
    </div>
</template>
<style>

.home-section{
    max-width: 1500px;
    display: flex;
position: relative;
    width: 100%;
    justify-content: center;
  
}


.box-area,.video-area{
max-width: 50%;
width: 100em;
display: flex;
flex-direction: column;
}

.box-area{

}
.black-sheet{
    position:absolute;
    height: 100%;
    width: 49.7%;
    background-color: rgb(10, 10, 10,0.2);
    border-radius:30px ;
    display: flex;
    flex-direction: column;
}

.video-area{
    height: 750px;
    margin-left: 10px;

}

#video-box{
    object-fit: cover;
    border-radius:30px ;

}
.little-card{
   
    max-width: 250px;
    max-height: 150px;
    width: 100%;
    height: 100%;
    margin-top: 30px;
    margin-left: auto;
    background-image: linear-gradient(rgba(91, 54, 119, 0.2),rgba(37, 36, 36, 0.2));
    border-radius: 20px;

    
    
    margin-right: 50px;
}
.circle{
    position: fixed;
    transform: translate(20px,30px);
    width: 30px;
    height: 30px;
    background-color: black;
    border-radius: 50%;
    z-index: 8;
}
.c2{
    z-index: 9;
    background-color: wheat;
    transform: translate(40px,30px);
}

.c3{
    z-index: 8;
    background-color: rgba(224, 10, 10, 0.74);
    transform: translate(60px,30px);
}
.c4{
    background-color: transparent;
    border: 1px dashed #887F7F;
    transform: translate(93px,30px);
    text-align: center;
    color: #B8A9A9;
}
.little-card-text{
    font-family: "Kurale", serif;
  font-weight: 300;
  font-style: normal;
  font-size: 16px;
  text-align: right;
  transform: translate(-20px,90px);
  color: #B8A9A9;
}
.button-video{

    background-color: #CABA90;
    max-width: 200px;
    color: #3F3D3D;
    font-family: "Karla", sans-serif;
  font-optical-sizing: auto;
  font-weight: 700;
  font-style: normal;
  font-size: 21px;
  border-radius:30px ;
  padding: 7px 25px;
 
  }

  .image-arrow{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #CABA90;
    max-width: 100px;
    margin-left: 10px;
 
    padding: 2px 25px;
    border-radius:30px ;
  }

  .little-crd-btn-holder{
    display: flex;
    margin-left: auto;
    

    max-width: 310px;
    margin-top: auto;
    margin-bottom: 20px;
    margin-right: 30px;
    flex-wrap: wrap;
  }

  .start-box{
    display: flex;
    justify-content: center;
    align-items: center;

    background-color: #3F3D3D;

    width: 100%;
    max-height:250px ;
    height: 100%;
    border-radius:20px ;

  }
  .second-box{
    background-color: #252424;
    width: 100%;
    height: 100%;
    border-radius:20px ;
    border: 1px dashed #CABA90;
    margin-top: 15px;
  }

  .head-text-box2{
    font-size: 50px;
    color: #B8A9A9;
    max-width: 100px;
    line-height: normal;

  }
  .hold-text-boxx2{
    max-width: 500px;
    margin: 20px;
  }
  .sub-text-box2{
    display: inline;
    font-size: 17px;
    color: #B8A9A9;

    font-weight: 300;
    line-height: normal;
 
  }

  .highlith{
    
    display: inline;
    font-size: 17px;
    color: #252424;
    font-weight: 500;
    
    background-color:#CABA90 ;
    border-radius: 5px;

  }

  .card-holder{
    display: flex;
    margin: 20px;
  }
  .card1{
    display: flex;
    flex-direction: column;
    background-color: #3F3D3D;
    max-width: 200px;
    max-height: 160px;
    width: 100em;
    height: 100em;
    border-radius: 15px;
    margin-top: 10px;
    margin-right: 10px;
  }
  .percent{
    color: #CABA90;
    font-size: 50px;
    margin-left: 30px;
    margin-top: 10px;
  }
  .cd-btm-txt{

    color: #887F7F;
    font-size: 17px;
    margin-top: auto;
    margin-left: auto;
    margin-right: 15px;
    text-align: right;
    margin-bottom: 20px;


  }

  .arrowNEw{
    display: flex;
    justify-content: center;
    align-self: start;
  border: 1px dashed #887F7F;
  max-width:100px ;
  max-height: 60px;
  padding: 0px 60px ;
  border-radius: 10px;
  margin: auto;
  }

  .text-box{
    color: #887F7F;
    font-family: "Laila", serif;
  font-weight: 400;
  font-style: normal;
  font-size: 55px;
  }

  .start-box:hover{
    background-color:#CABA90;
  }


</style>


