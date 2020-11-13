<template>
  <div>
  <nav class="navbar navbar-expand-lg sticky-top">
  <div class="container">
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
    <b-navbar toggleable="lg" >
      <b-navbar-brand to="/"><img class="auto auto1" src="~assets/images/eso02logo.png" alt=""></b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle> 

      <b-collapse id="nav-collapse" is-nav>

        <b-navbar-nav>
          <li class="nav-item">
            <a class="nav-link" href="/whyesopos"> <span class="learn">Why Esopos</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/solution">Resourses</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/blog">Blog</a>
          </li>
        </b-navbar-nav>
        <b-navbar-nav>
            <button type="button" class="btn esobtn_1 btn-outline-danger">Get The App</button>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

  </div>
</nav>
</div>
</template>

<style>
  @media screen and (min-width: 1100px){
    .navbar-nav {
      position: relative;
      left: 90px;
    }
    .auto {
      position: relative;
      left: 80px;
      margin-left: 25px;
    }
  }

  @media screen and (min-width: 1000px){
    #nav-collapse{
      color: #000000;
    }
    .nav-link{
      left: 150px;
      margin: 0px 13px 0px;
    }
    .navbar-light .navbar-nav .nav-link{
      color: #000000;
    }
    .auto {
      margin-left: 55px;
    }
    img {
      margin-bottom: -20px;
    }
  }

  .esobtn_1 {
    position: relative;
    left: 310px;
    top: 5px;
    padding: 7px 28px 7px;
    border: 3px solid #455A64;
    color: #E0115F;
    font-weight: bold;
  }

  @media screen and (max-width: 420px) {
      .auto {
        position: relative;
        right: 60px;
        left: 5px;
        bottom: 10px;
      }
      .auto1{
        margin-bottom: -25px;
      }
    #nav-collapse{
      background: #E0115F;
      color: #ffffff;
      padding-bottom: 10px;
    }
    .navbar-light .navbar-nav .nav-link{
      color: #ffffff;
      padding-left: 10px;
      padding-right: 10px;
    }
  }


  nav {
    background: #FFFFFF;
    
    height: 70px;
    left: 0px;
    top: 0px;
    position: fixed;
  }

  .navbar {
    background: #FFFFFF;
    position: fixed;
    z-index: 32px;
  }

  @media screen and (min-width: 1000px){
      .navbar {
        width: 100%;
      }
  }

  .auto {
    width: 130.02px;
    
    position: relative;
    
  }

  .nav-item {
    font-size: 11px;
  }

  .nav-link {
   position: relative;
    top: 6px;
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 15px;
    line-height: 20px;
    color: #40337B;
  }


</style>

