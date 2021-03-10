<template>
  <footer>
    <div class="main_container">
      <div class="content_footer">
        <div class="footer_main_logo font17 semibold relative">
<!--          <a href="javascript:void(0)"><img src="http://pi-frontend.cpco.ro/images/Logo_footer_Asset_3@2x.png" alt="Asociatia Ortodoxia Tinerilor" class="logo-foto"></a>-->
          <a href="javascript:void(0)"><img src="@/assets/Logo_footer.png" class="logo-foto"/></a>
          <!--                <p>Un proiect al <span class="silver">Asociatiei Ortodoxia Tinerilor</span></p>-->
        </div>
        <div class="footer_second_logo">
          <a href="javascript:void(0)"><img src="@/assets/fcp_logo.jpg" alt="fericiti cei prigoniti"></a>
        </div>
        <div class="footer_contact font17">
          <ul class="footer_contact_net mb20">
            <li><a href="javascript:void(0)" class="fb"><i class="fa fa-facebook" aria-hidden="true"></i></a>
            </li>
            <li><a href="javascript:void(0)"><i class="fa fa-youtube" aria-hidden="true"></i></a></li>
            <li><a href="javascript:void(0)"><i class="fa fa-paypal" aria-hidden="true"></i></a></li>
            <li><a href="javascript:void(0)"><i class="fa fa-rss" aria-hidden="true"></i></a></li>
          </ul>
          <ul class="footer-link">
            <li><a href="javascript:void(0)">Despre proiect</a></li>
            <li><a href="javascript:void(0)">Bibliografie</a></li>
            <li><a href="javascript:void(0)">Sustine</a></li>
            <li><a href="javascript:void(0)">Contact</a></li>
          </ul>
        </div>
      </div>
    </div>
  </footer>

</template>

<script>

export default {
name: "TheFooter"
}
</script>

<style scoped>
.logo-foto{
  height: 6.5rem;
}
footer .content_footer {
  border-top:3px solid red;
  /*border-bottom:5px solid red;*/
  padding:40px 0;
  font-weight: 600;
}

.footer_second_logo {
  display: inline-block;
  vertical-align: middle;
}

footer a { color:#000; }

.footer_main_logo {
  display: inline-block;
  vertical-align: middle;
  letter-spacing: 2px;
}

.footer_main_logo p {
  position: absolute;
  left: 90px;
  bottom:0;
}

.silver { color:#8c8c8c; }

.footer_contact {
  display: inline-block;
  vertical-align: middle;
  padding-right: 67px;
}

.footer_contact ul li {
  list-style-type: none;
  margin-bottom: 5px;
}

.footer_contact ul.footer_contact_net li { display: inline-block; }

.footer_contact_net a {
  background: #dd0000;
  color: #fff;
  padding: 3px 7px;
  border-radius: 100%;
}

.footer_contact_net a.fb { padding: 3px 8px; }
.footer-link{
  text-align: start;
}
.footer-link a {
  text-decoration: none;
}
@media screen and (max-width: 768px){
  .logo-foto{
    display: none;
  }
}
</style>