<template>
    <div class="div">
    <Head/>
     <section>
    <div class="container">
        <div class="row">
             <div class="col-lg-12 col-xl-12 esopos-1">
                <h5>A Solution that's Perfect <br> for Business Like Yours</h5>
            </div>
        </div>
    </div>

        <div class="container container1">
            <div class="row">
                <div class="col-sm-12">
                    <div class="search_wrap search_wrap_2">
                        <div class="search_box">
                            <div class="btn btn_common">
                                <i class="fas fa-search"></i>
                            </div>
                            <input type="text" class="input" placeholder="Search our help articles">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <div class="container">
        <div class="row">
            <div class="col-lg-4 col-xl-4">
            <div class="card2" style="width: 18rem; ">
                    <div class="card-body">
                        <div class="bank">
                            <h5 class="card-title">General</h5>
                        </div>
                        <p class="card-textt">Everything you need to know about Esopos</p>
                        </div>
                    </div>
            </div> 
            <div class="col-lg-4 col-xl-4">
            <div class="card2" style="width: 18rem; ">
                    <div class="card-body">
                        <div class="bank">
                            <h5 class="card-title">Getting Started</h5>
                        </div>
                        <p class="card-textt">Everything you need to know to get started</p>
                        </div>
                    </div>
            </div> 
            <div class="col-lg-4 col-xl-4">
            <div class="card2" style="width: 19rem; ">
                    <div class="card-body">
                        <div class="bank">
                            <h5 class="card-title">Product and Inventory</h5>
                        </div>
                        <p class="card-texttt">Everything you need to know about importing creating and managing your products services</p>
                        </div>
                    </div>
            </div> 
        </div>
    </div>   

    <section class="starting">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 col-xl-12">
                    <h1>Why Esopos</h1>
                    <p class="ptag">Registration is FREE and you can instantanely publish your <br> chatbots on Facebook Messenger, Whatsapp, Telegram, Web <br> Sites, Slack, Amazon Alexa and Google Assistant</p>
                </div>
            </div>
        </div>
    </section>                 
    </div>
</template>

<script>
import Head from "~/components/head";
export default {
  components: {Head},

  mounted(){
    AOS.init();
  }
}
</script>

<style>

.div {
    overflow: hidden;
    height: 100%;
  }

section{
    background: #F3F8FE 0% 0% no-repeat padding-box;
opacity: 1;
position: relative;
bottom: 8px;
}

  .card2 {
    background: #FFFFFF 0% 0% no-repeat padding-box;
    border-radius: 5px;
    opacity: 1;
    transform: translateY(10px);
    transition: 0.2s all;
    position: relative;
    left: -10px;
    padding-bottom: 20px;
    box-shadow: 0 0 2px 1px rgba(0, 0, 0, 0.1);
    margin-top: 100px;
}

.card-title{
    letter-spacing: 0px;
    color: #06083d;
    opacity: 1;
    text-align: center;
    font-size: 16px;
    font-weight: bold;
    font-family: 'Open Sans', sans-serif;
    position: relative;
    top: 10px;
}

.card-textt {
    font-size: 13px;
    text-align: center;
    margin-top: 45px;
    letter-spacing: 0px;
    color: #000000;
    opacity: 3;
    font-family: 'Roboto', sans-serif;
}

.card-texttt {
    font-size: 9px;
    text-align: center;
    margin-top: 45px;
    letter-spacing: 0px;
    color: #000000;
    opacity: 3;
    font-family: 'Roboto', sans-serif;
}

.esopos-1 h5{
    margin-top: 140px;
    text-align: center;
    letter-spacing: 0px;
    color: #40337B;
    opacity: 1;
    font-family: 'Open Sans', sans-serif;
    font-weight: 900;
    font-size: 28px;
    line-height: 33px;
}

.container1 .input {
    border: 0;
    outline: none;
    color: #8b7d77;
    background: #FFFFFF 0% 0% no-repeat padding-box;
    box-shadow: 0px 3px 6px #00000029;
    opacity: 1;
    text-align: center;
    font-size: 10px;
    font-family: 'Roboto', sans-serif;
    letter-spacing: 0px;
    color: #000000;
    opacity: 1;
}

.containerrr .input {
    border: 0;
    outline: none;
    color: #8b7d77;
    background: #FFFFFF 0% 0% no-repeat padding-box;
    box-shadow: 0px 3px 6px #00000029;
    opacity: 1;
    text-align: center;
    font: normal normal normal 30px/65px Roboto;
    letter-spacing: 0px;
    color: #000000;
    opacity: 1;
    position: relative;
    bottom: 50px;
}

.search_wrap {
    width: 500px;
    margin: 70px auto;
    position: relative;
    right: 53px;
    margin-bottom: 90px;
}

.search_wrap .search_box {
    position: relative;
    width: 600px;
    height: 60px;
}

.search_wrap .search_box .input {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    padding: 30px 20px;
    padding-right: 100px;
    border-radius: 3px;
    font-size: 18px;
}

.search_wrap .search_box .btn {
    position: absolute;
    top: 0;
    right: 0;
    width: 60px;
    height: 100%;
    background: #FFFFFF 0% 0% no-repeat padding-box;
    color: black;
    opacity: 1;
    z-index: 1;
    cursor: pointer;
}

.search_wrap .search_box .btn:hover {
    background: #708bd2;
}

.search_wrap .search_box .btn.btn_common .fas {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: rgb(145, 131, 131);
    font-size: 20px;
}

.search_wrap.search_wrap_1 .search_box .btn {
    right: 0;
    border-top-right-radius: 3px;
    border-bottom-right-radius: 3px;
}

.search_wrap.search_wrap_2 .search_box .btn {
    left: 0;
    border-top-left-radius: 3px;
    border-bottom-left-radius: 3px;
}

.search_wrap.search_wrap_2 .search_box .input {
    padding-left: 80px;
}


.starting {
    margin-top: 100px;
    background: #EFEFFE 0% 0% no-repeat padding-box;
    box-shadow: 0px 3px 6px #00000029;
    opacity: 1;
    width: 70vw;
    position: relative;
    left: 155px;
    padding: 20px 20px 20px;
}

.starting h1 {
    text-align: center;
    font-size: 25px;
    font-family: 'Open Sans', sans-serif;
    letter-spacing: 0px;
    color: #707070;
    opacity: 1;
}

.starting p {
    text-align: center;
    font-size: 14px;
    font-family: 'Roboto', sans-serif;
    letter-spacing: 0px;
    color: #707070;
    opacity: 1;
    position: relative;
    left: 10px;
}

</style>