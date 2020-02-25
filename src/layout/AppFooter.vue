<style>


/* Wrapper */
.icon-button {
	background-color: white;
	border-radius: 3.6rem;
	cursor: pointer;
	display: inline-block;
	font-size: 2.0rem;
	height: 3.6rem;
	line-height: 3.6rem;
	margin: 0 5px;
	position: relative;
	text-align: center;
	-webkit-user-select: none;
	   -moz-user-select: none;
	    -ms-user-select: none;
	        user-select: none;
	width: 3.6rem;
}

/* Circle */
.icon-button span {
	border-radius: 0;
	display: block;
	height: 0;
	left: 50%;
	margin: 0;
	position: absolute;
	top: 50%;
	-webkit-transition: all 0.3s;
	   -moz-transition: all 0.3s;
	     -o-transition: all 0.3s;
	        transition: all 0.3s;
	width: 0;
}
.icon-button:hover span {
	width: 3.6rem;
	height: 3.6rem;
	border-radius: 3.6rem;
	margin: -1.8rem;
}
.twitter span {
	background-color: #4099ff;
}
.facebook span {
	background-color: #3B5998;
}
.google-plus span {
	background-color: #db5a3c;
}

/* Icons */
.icon-button i {
	background: none;
	color: white;
	height: 3.6rem;
	left: 0;
	line-height: 3.6rem;
	position: absolute;
	top: 0;
	-webkit-transition: all 0.3s;
	   -moz-transition: all 0.3s;
	     -o-transition: all 0.3s;
	        transition: all 0.3s;
	width: 3.6rem;
	z-index: 10;
}
.icon-button .icon-twitter {
	color: #4099ff;
}
.icon-button .icon-facebook {
	color: #3B5998;
}
.icon-button .icon-google-plus {
	color: #db5a3c;
}
.icon-button:hover .icon-twitter,
.icon-button:hover .icon-facebook,
.icon-button:hover .icon-google-plus {
	color: white;
}
.searchBox {
    
  width:200px;
    top: 50%;
    left: 50%;
    margin-left: 100px;
    transform:  translate(-50%,50%);
    background: #cbd4e0;
    height: 40px;
    border-radius: 40px;
    padding: 10px;

}



.searchBox:hover > .searchButton {
  background: white;
  color : #2f3640;
}

.searchButton {
    color: white;
    float: right;
    width: 40px;
    height: 40px;
        margin-top: -10px;
    border-radius: 50%;
    background: #bbc6d4;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: 0.4s;
}

.searchInput {
    border:none;
    background: none;
    outline:none;
    float:left;
    padding: 0;
    color: rgb(53, 32, 32);
    font-size: 16px;
    transition: 0.4s;
    line-height: 40px;
    width: 100px;
    margin-top: -10px;

}
</style>
<template>
       <footer class="page-footer font-small mdb-color lighten-3 pt-4">

  <!-- Footer Links -->
  <div class="container text-center text-md-left">

    <!-- Grid row -->
    <div class="row">

      <!-- Grid column -->
      <div class="col-md-4 col-lg-3 mr-auto my-md-4 my-0 mt-4 mb-1">

        <!-- Content -->
        <h5 class="font-weight-bold text-uppercase mb-4" style="margin-bottom: 2rem;">PRODUCT</h5>
        
        <h5 class="font-weight-bold text-uppercase mb-4" style="margin-bottom: 2rem;">Personal</h5>
        <h5 class="font-weight-bold text-uppercase mb-4" style="margin-bottom: 2rem;">Business</h5>
        <h5 class="font-weight-bold text-uppercase mb-4" style="margin-bottom: 2rem;">Pricing</h5>
        <h5 class="font-weight-bold text-uppercase mb-4" style="margin-bottom: 2rem;">Login</h5>

      </div>
      <!-- Grid column -->

      <hr class="clearfix w-100 d-md-none">

      <!-- Grid column -->
      <div class="col-md-2 col-lg-2 mx-auto my-md-4 my-0 mt-4 mb-1">

        <!-- Links -->
        <h5 class="font-weight-bold text-uppercase mb-4" style="margin-bottom: 2rem;">COMPANY</h5>
                <h5 class="font-weight-bold text-uppercase mb-4" style="margin-bottom: 2rem;">About</h5>

        <h5 class="font-weight-bold text-uppercase mb-4" style="margin-bottom: 2rem;">Blog</h5>

        <h5 class="font-weight-bold text-uppercase mb-4" style="margin-bottom: 2rem;">Careers</h5>

        <h5 class="font-weight-bold text-uppercase mb-4" style="margin-bottom: 2rem;">Contact Us</h5>


        <ul class="list-unstyled">
          <li>
            <p>
              <a href="#!">PROJECTS</a>
            </p>
          </li>
          <li>
            <p>
              <a href="#!">ABOUT US</a>
            </p>
          </li>
          <li>
            <p>
              <a href="#!">BLOG</a>
            </p>
          </li>
          <li>
            <p>
              <a href="#!">AWARDS</a>
            </p>
          </li>
        </ul>

      </div>
      <!-- Grid column -->

      <hr class="clearfix w-100 d-md-none">

      <!-- Grid column -->
      <div class="col-md-4 col-lg-3 mx-auto my-md-4 my-0 mt-4 mb-1">

        <!-- Contact details -->
        <h5 class="font-weight-bold text-uppercase mb-4">HELP CENTER</h5>
        <h5 class="font-weight-bold text-uppercase mb-4">FAQ</h5>

        <h5 class="font-weight-bold text-uppercase mb-4">Insurance</h5>

        <h5 class="font-weight-bold text-uppercase mb-4">Agreement</h5>

        

      </div>
      <!-- Grid column -->

      <hr class="clearfix w-100 d-md-none">

      <!-- Grid column -->
      <div class="col-md-2 col-lg-3 text-center mx-auto my-4">

        <!-- Social buttons -->
        <h5 class="font-weight-bold text-uppercase mb-4">STAY IN TOUCH</h5>

       <p>Join our mailing list to getnupdates. We respect your privacy.</p>
 <div class="searchBox">

            <input class="searchInput" type="text" name="" placeholder="Search">
            <button class="searchButton" href="#">
                <i class="material-icons">
                    <svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height="24" viewBox="0 0 24 24" width="24"><g><rect fill="none" height="24" width="24"/></g><g><g><path d="M6.05,8.05c-2.73,2.73-2.73,7.15-0.02,9.88c1.47-3.4,4.09-6.24,7.36-7.93c-2.77,2.34-4.71,5.61-5.39,9.32 c2.6,1.23,5.8,0.78,7.95-1.37C19.43,14.47,20,4,20,4S9.53,4.57,6.05,8.05z"/></g></g></svg>
                </i>
            </button>
        </div>
        <div style="
    margin-top: 50px;
    margin-left: -40px;
">
          <a href="https://google plus" ><img src="https://image.flaticon.com/icons/png/512/145/145804.png" data-src="https://image.flaticon.com/icons/png/512/145/145804.png" srcset="https://image.flaticon.com/icons/png/512/145/145804.png 4x" alt="" title="" width="64" height="64" class="lzy lazyload--done"></a>

  <a href="https://twitter.com/minimalmonkey" ><img src="https://image.flaticon.com/icons/png/512/179/179342.png" data-src="https://image.flaticon.com/icons/png/512/179/179342.png" srcset="https://image.flaticon.com/icons/png/512/179/179342.png 4x" alt="" title="" width="64" height="64" class="lzy lazyload--done"></a>
<a href="https://facebook.com"> <img src="https://image.flaticon.com/icons/png/128/179/179319.png" data-src="https://image.flaticon.com/icons/png/128/179/179319.png" srcset="https://image.flaticon.com/icons/svg/179/179319.svg 4x" alt=" free icon" title=" free icon" width="64" height="64" class="lzy lazyload--done"></a>
      </div>
      </div>
      <!-- Grid column -->

    </div>
    <!-- Grid row -->

  </div>
  <!-- Footer Links -->

  <!-- Copyright -->
  <div class="footer-copyright text-center py-3">© 2020 Copyright:
  </div>
  <!-- Copyright -->

</footer>
<!-- Footer -->
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
