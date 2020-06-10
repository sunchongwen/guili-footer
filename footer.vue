<template>
  <div class="footer-all">
    <section id="contact" class="contact">
      <b-container fluid class="product-css">
        <b-row>
          <b-col class="footer-bg-contact" md="12" lg="4" sm="12" xs="12">
            <div class="footer-bg">
              <div class="icon icon-icon">
                <i class="fa fa-phone-square" aria-hidden="true"></i>
              </div>
              <div class="icon">
                <h1 class="contact">Contact Information</h1>
              </div>
            </div>
            <h6>Guili Investment Ltd</h6>
            <h6>235 Eugenie St W #215, Windsor, ON N8X 2X7</h6>
            <h6>+1 (519) 551-9058</h6>
          </b-col>
          <b-col md="12" lg="4" sm="12" xs="12">
            <div class="footer-bg padding-10">
              <div class="icon icon-icon">
                <i class="fa fa-podcast" aria-hidden="true"></i>
              </div>

              <div class="icon">
                <h1>Email Address</h1>
              </div>
            </div>
            <h6>guili.investment@gmail.com</h6>
          </b-col>
          <b-col md="12" lg="4" sm="12" xs="12">
            <div class="footer-bg">
              <div class="icon icon-icon">
                <i class="fa fa-address-book" aria-hidden="true"></i>
              </div>
              <div class="icon">
                <h1>Where To Find Us</h1>
              </div>
            </div>
            <div>
              <iframe
                width="100%"
                height="200"
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2951.690913031272!2d-83.022922184309!3d42.28512084782297!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x883b2c441ca88a67%3A0xec6c6b73cfb718a2!2sGuili-Investment!5e0!3m2!1sen!2sca!4v1591731320939!5m2!1sen!2sca"
                frameborder="0"
                style="border:0;"
                allowfullscreen
                aria-hidden="false"
                tabindex="0"
              ></iframe>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </section>
  </div>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.icon-icon {
  font-size: 3rem;
}
.icon {
  display: inline-block;
  margin-left: 1rem;
}
h6 {
  font-size: 2rem;
  padding: 1rem;
}
.padding-top {
  padding-top: 10rem;
}
.footer-all {
  color: beige;
  background-color: #333;
  opacity: 0.8;
  font-size: 10rem;
}

iframe {
  border-radius: 1rem;
}
</style>
