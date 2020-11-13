<template>
    <div class="div">
    <Head/>
    <section class="sectionsubmit">
        <div class="container">
            <div class="row">
            <div class="col-lg-12 col-xl-12 submit">
                <h2>Cant find answers to your question <br> Send us a request and we will get back <br> to you.</h2>
            </div>
            </div>
        </div>
    </section>
        <div class="container container1">
            <div class="row">
            <div class="col-lg-12 col-xl-12 request">
                <h3>Submit Request</h3>
            </div>
               <div class="col-lg-8 col-xl-12">
                <form action="/action_page.php" class="form_">
                    <div class="form-group">
                        <label for="exampleInputEmail1">Email address</label>
                        <input  class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
                    </div>
                    <div class="form-group">
                        <label for="exampleInputPassword1">Password</label>
                        <input class="form-control" id="exampleInputPassword1" placeholder="Password">
                    </div>
                   
                    <div class="form-group">
                        <label for="exampleFormControlTextarea1">Subject</label>
                        <textarea class="form-control" id="exampleFormControlTextarea1" rows="8"></textarea>
                        <small id="emailHelp" class="form-text text-muted">Enter details of your request</small>
                    </div>

                        <input type="file" id="myFile" name="filename">
                    
                   <div class="btn-">
                     <button type="submit" class="btn esoposbtn-">Submit</button>
                   </div>
                </form>
               </div>
            </div>
        </div>
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
    .form_ {
        margin-top: 100px;
    }

    .form_ .btn- {
        margin-top: 30px;
    }

    .container1 {
        margin-bottom: 50px;
    }

    .form_ label {
        padding-bottom: 25px;
        letter-spacing: 0px;
        font-weight: 500;
        color: #40337B;
        opacity: 1;
        font-family: 'Open Sans', sans-serif;
        font-size: 17px;
        position: relative;
        top: 5px;
    }

    .form_ input {
        padding: 25px 9px 25px;
    }

    .esoposbtn- {
        padding: 10px 80px 10px;
        background: #E0115F 0% 0% no-repeat padding-box;
        border: 1px solid #E0115F;
        border-radius: 8px;
        opacity: 1;
        color: white;
    }

    .submit h2 {
        margin-top: 80px;
        position: relative;
        top: 60px;
        letter-spacing: 0px;
        color: #40337B;
        opacity: 1;
        font-size: 30px;
        text-align: center;
    }

    .sectionsubmit {
        background: #F3F8FE 0% 0% no-repeat padding-box;
        opacity: 1;
        padding-bottom: 160px;
    }

    .request h3{
        position: relative;
        top: 57px;
        letter-spacing: 0px;
        color: #40337B;
        font-family: 'Open Sans', sans-serif;
        font-weight: bold;
    }
</style>