<template>
  <div>
      <header class="home home-card">
        <div class="home-wrapper wrapper">
          <div class="home-container">
            <div class="home-container-text">
              <div class="home-container-title">
                <h1 class="home-title"><span class="title-bold">Payement Automation</span> for tech companies </h1>
                <h2 class="home-description">Automate payments across banks with a <span class="description-bold">single API</span></h2>
              </div>
              <div class="home-container-button">
                <button class="expert-button">
                  <!-- faire un lien plus tard vers la page -->
                  <p class="expert-button-text">Talk to an expert &#8594</p>
                </button>
              </div>
            </div>
            <div class="home-container-logo">
            </div>
          </div>
        </div>
      </header>
      <div class="features-wrapper wrapper">
        <div class="features-container coverage">
          <div class="features-container-text">
            <div class="features-type-container">
              <img src="../assets/img/coverageicon.svg" alt="">
              <p class="features-type">Coverage</p>
            </div>
            <h1 class="features-title">We develop bank integrations so you don't have to</h1>
            <p class="features-description">Integrate a single API for all your banks and payment methods. We handle EBICS, ISO 20022, and banking complexity for you.</p>
            <button class="features-button">
              <p class="features-button-text">Explore Coverage</p>
            </button>
          </div>
          <div class="features-vimeo">
            <iframe class="ArticleSideBoxVideo" src="https://player.vimeo.com/video/657468100" width="100%" height="130%" frameborder="0"></iframe>
          </div>
        </div>
      </div> <!--Coverage-->
      <div class="features-wrapper wrapper">
        <div class="features-container automation">
          <div class="features-container-text">
            <div class="features-type-container">
              <img src="../assets/img/automationicon.svg" alt="">
              <p class="features-type">Automation</p>
            </div>
            <h1 class="features-title">Build custom end-to-end payment workflows</h1>
            <p class="features-description">Automate payments from initiation to approval to reconciliation. Receive real-time notifications as payments are processed.</p>
            <button class="features-button">
              <p class="features-button-text">Explore automation</p>
            </button>
          </div>
          <div class="features-vimeo">
            <iframe class="ArticleSideBoxVideo" src="https://player.vimeo.com/video/657468100" width="100%" height="130%" frameborder="0"></iframe>
          </div>
        </div>
      </div><!--Automation-->
      <div class="features-wrapper wrapper">
        <div class="features-container developpers">
          <div class="features-container-text">
            <div class="features-type-container">
              <img src="../assets/img/developersicon.svg" alt="">
              <p class="features-type">Developers</p>
            </div>
            <h1 class="features-title">A powerful API and webhooks developers will love</h1>
            <p class="features-description">Integrate our API and webhooks into your own product and tools. Test in sandbox and launch in production in days.</p>
            <button class="features-button">
              <p class="features-button-text">Explore Developers</p>
            </button>
          </div>
          <div class="features-vimeo">
            <iframe class="ArticleSideBoxVideo" src="https://player.vimeo.com/video/657468100" width="100%" height="130%" frameborder="0"></iframe>
          </div>
        </div>
      </div> <!--Developpers-->
      <div class="payement-card" >
        <div class="payement-text-container">
          <h1 class="payement-title"><span class="title-bold">Payement Automation</span> <br> for tech companies </h1>
          <button class="expert-button">
            <p class="expert-button-text">Talk to an expert &#8594</p>
          </button>
          <p class="payement-trust-text">They trust us !</p>
        </div>
      </div>
      <footer class="footer">
        <div class="footer-container wrapper">
          <div class="footer-container-links">
            <h1 class="footer-title">Features</h1>
            <ul class="footer-links-list">
              <li class="footer-links">Platform</li>
              <li class="footer-links">Coverage</li>
              <li class="footer-links">API Docs</li>
              <li class="footer-links">Security</li>
            </ul>
          </div>
          <div class="footer-container-links">
            <h1 class="footer-title">About</h1>
            <ul class="footer-links-list">
              <li class="footer-links">About us</li>
              <li class="footer-links">Careers</li>
              <li class="footer-links">Blog</li>
              <li class="hidden">space</li>
            </ul>
          </div>
          <div class="footer-container-links">
            <h1 class="footer-title hidden">lorem</h1>
            <ul class="footer-links-list">
              <li class="footer-links">Use Cases</li>
              <li class="footer-links">FAQ</li>
              <li class="footer-links">Mentions Légales</li>
              <li class="hidden">space</li>
            </ul>
          </div>
          <div class="footer-container-links">
            <h1 class="footer-title">Social</h1>
            <ul class="footer-links-list">
              <li class="footer-links">Linkedin</li>
              <li class="footer-links">Twitter</li>
              <li class="hidden">lorem</li>
              <li class="hidden">lorem</li>
            </ul>
          </div>
        </div>
        <div ><p class="copyright">© 2021  Numeral. Tout droits réservés</p></div>
      </footer>
  </div>

</template>

<script>

export default {
  name: 'IndexPage'
    }
</script>

<style>
  .wrapper{
    padding-left: 10%;
    padding-right: 10%;
  }
  .expert-button{
    background-color: #1E3076;
    border: none;
    border-radius:8px;
    width:200px;
    height:50px;
    padding-top: 10px;
    padding-left: 15px;
    padding-right: 15px;
  }
  .expert-button-text{
    color: white;
    font-size: 16px;
    font-weight: 700;

  }
  /*css home*/
  header.home {
    width: 100%;
    height: 400px;
    background-color: #3B61F4;
  }

  /*home-container-text*/
  .home-container-title{
    width: 50%;
    padding-bottom:3%
  }
  .home-title{
    color: white;
    font-size: 56px;
    font-weight: 400;
  }
  .title-bold {
    font-weight: 700;
  }
  .home-description{
    color: #CFD9FF;
    font-size: 18px;
    font-weight: 400;
  }
  .description-bold{
    color: white;
  }
  /* css features */
  .features-wrapper{
    padding-top: 3%;
    padding-bottom:3%;
  }
  .features-container{
    display:flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
  }
  .features-type-container {
    display:flex;
    flex-direction: row;
    align-items: center;
  }
  .features-container-text{
    width: 40%;
  }
  .features-type{
    display:flex;
    flex-direction: column;
    justify-content:center;
    color: #3B61F4;
    font-size: 12px;
    font-weight: 700;
  }
  .features-title{
    font-size: 38px;
    font-weight: 700;
  }
  .features-description{
    font-size: 18px;
    font-weight: 400;
  }
  .features-button{
    background-color:#EAEEFF;
    border: none;
    border-radius: 8px;
  }
  .features-button-text{
    padding-top: 10px;
    padding-left: 10px;
    padding-right: 10px;
    font-size: 14px;
    font-weight: 700;
    color:#3B61F4;

  }
  .features-vimeo{
    display: flex;
    justify-content:center;
    align-items:center;
    width: 60%;
  }

  /* css payement-card */
  .payement-card {
    width:100%;
    background-color: #3B61F4;
    display: flex;
    justify-content: center;
  }
  .payement-text-container {
    display: flex;
    flex-flow: column wrap;
    width:50%;
    align-items: center;
  }
  .payement-title {
    color: white;
    font-size: 56px;
    font-weight: 400;
    text-align: center;
    padding-top: 7%;
    padding-bottom:5%
  }
  .payement-trust-text {
    font-size: 14px;
    color: white;
    opacity: 80%;
    padding: 5% 0 5% 0;
  }
  /* footer */
  .footer{
    background-color: #0F183B;
    padding-top: 4%;
  }
  .footer-container {
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
  }
  .footer-container-links{
  width: 15%;
  }
  .footer-title {
    color: white;
    font-size:18px;
    font-weight: 700;
  }
  .footer-links-list{
    list-style: none;
    padding: 0;
  }
  .hidden{
    color: transparent;
  }
  .footer-links{
    color: white;
    font-size: 14px;
    font-weight: 400;
  }
  .copyright{
    color: white;
    margin: 0 auto;
    font-size: 14px;
    text-align: center;
  }
</style>
