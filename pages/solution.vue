<template>
    <div class="div">
    <Head/>
    <section class="sectionsubmit">
        <div class="container">
            <div class="row">
            <div class="col-lg-12 col-xl-12 submit">
                <h2>A Solution that's Perfect <br> for Business Like Yours</h2>
            </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container" style="margin-top: 100px">
            <div class="row">
            <div class="col-lg-5 col-xl-5">
                <div class="row">
                    <div class="col-lg-11 col-xl-11 button"  @click="showTab1">
                        <p class="atag" href="#" >Buying SMS Unit</p>
                    </div>
                    <div class="col-lg-11 col-xl-11" @click="showTab2">
                        <p class="atag1" href="#">Sending New Message</p>
                    </div>
                    <div class="col-lg-11 col-xl-11" @click="showTab3">
                        <p class="atag1" href="#">Draft Message</p>
                    </div>
                    <div class="col-lg-11 col-xl-11" @click="showTab4">
                        <p class="atag1" href="#">Groups</p>
                    </div>
                    <div class="col-lg-11 col-xl-11" @click="showTab5">
                        <p class="atag1" href="#">Restock</p>
                    </div>
                </div>
            </div>

            <div class="col-lg-7 col-xl-7 onclick">
                <div  class="row">
                    <div  class="col-lg-12 col-xl-12" v-if="tab1">
                        <p>Whether you're a single location, single register business; have multiple locations with multiple registers; or anything in-between, Vend can be customised to suit your set up!</p>
                        <p>This allows you to accurately track what has been sold, inventory levels, and at different locations, making reconciliation and reporting easy.</p>
                        <p>Whether you're a single location, single register business; have multiple locations with multiple registers; or anything in-between, Vend can be customised to suit your set up!</p>
                        <p>This allows you to accurately track what has been sold, inventory levels, and at different locations, making reconciliation and reporting easy.</p>
                    </div>
                    <div  class="col-lg-12 col-xl-12" v-if="tab2">
                        <p>Whether you're a single location, single register business; have multiple locations with multiple registers; or anything in-between, Vend can be customised to suit your set up!</p>
                        <p>This allows you to accurately track what has been sold, inventory levels, and at different locations, making reconciliation and reporting easy.</p>
                    </div>
                    <div  class="col-lg-12 col-xl-12" v-if="tab3">
                        <p>This allows you to accurately track what has been sold, inventory levels, and at different locations, making reconciliation and reporting easy.</p>
                    </div>
                </div>
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
    data(){
        return {
            tab1 :true,
            tab2 :false,
            tab3 :false,
            tab4 :false,
            tab5 :false,
        }
    },
  mounted(){
    AOS.init();
  },
  methods:{
      showTab1() {
          this.tab1 = true;
          this.tab2 = false;
          this.tab3 = false;
          this.tab4 = false;
          this.tab5 = false;
      },
      showTab2() {
          this.tab2 = true;
          this.tab1 = false;
          this.tab3 = false;
          this.tab4 = false;
          this.tab5 = false;
      },
      showTab3() {
          this.tab3 = true;
          this.tab2 = false;
          this.tab1 = false;
          this.tab4 = false;
          this.tab5 = false;
      },
      showTab4() {
          this.tab4 = true;
          this.tab2 = false;
          this.tab3 = false;
          this.tab1 = false;
          this.tab5 = false;
      },
      showTab5() {
          this.tab5 = true;
          this.tab2 = false;
          this.tab3 = false;
          this.tab1 = false;
          this.tab1 = false;
      },
        close1() {
        return  this.name = false
      }

  }
}
</script>

<style>

.div {
    overflow: hidden;
    height: 100%;
  }
  
    .submit h2 {
        margin-top: 58px;
        position: relative;
        top: 90px;
        letter-spacing: 0px;
        color: #40337B;
        opacity: 1;
        line-height: 39px;
        font-size: 33px;
        text-align: center;
    }

    .onclick p {
        letter-spacing: 0px;
        color: #707070;
        opacity: 1;
        font-size: 16px;
        font-family: 'Roboto', sans-serif;
        position: relative;
        top: 20px;
    }

    .sectionsubmit {
        background: #F3F8FE 0% 0% no-repeat padding-box;
        opacity: 1;
        padding-bottom: 180px;
    }

    .atag {
        letter-spacing: 0px;
        color: #03155F;
        opacity: 1;
        text-decoration: none;
        font-weight: bold;
        font-size: 17px;
        font-family: 'Roboto', sans-serif;
        background: #F3F8FE 0% 0% no-repeat padding-box;
        box-shadow: 0px 6px 6px #00000029;
        border-radius: 3px;
        opacity: 1;
        padding: 18px 100px 18px;
        padding-left: 30px;
        width: 108%;
        cursor: pointer;
        transition: .3s;
    }
    .atag1 {
        letter-spacing: 0px;
        color: #03155F;
        opacity: 1;
        text-decoration: none;
        font-weight: bold;
        font-size: 16px;
        font-family: 'Roboto', sans-serif;
        background: #F3F8FE 0% 0% no-repeat padding-box;
        border-radius: 3px;
        opacity: 1;
        padding: 18px 140px 18px;
        padding-left: 30px;
        width: 109%;
        cursor: pointer;
        transition: .3s;
        outline: none;
    }

    .atag:hover,
    .atag1:hover
     {
        box-shadow: 2px 2px 2px rgb(58, 57, 101);
        border: 1px solid black;
        animation: anim-shadow .3s forwards;
    }
</style>