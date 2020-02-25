<style >
#cercle {
    width: 20px;
    height: 20px;
    border-radius: 20px;
    background: mediumslateblue;
}

</style>
<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-7" to="/">
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="#" target="_blank" rel="noopener"
                       class="btn-icon">
                
                        <span class="nav-link-inner--text"><h3>UPSHIFT</h3></span>
                    </a>
                </li>
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a href="#">
                        <img src="img/brand/blue.png">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
               <div id="cercle"></div>
                 <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="#" target="_blank" rel="noopener"
                       class="btn-icon">
                
                        <span class="nav-link-inner--text">Personnal</span>
                    </a>
                </li>
                               <div id="cercle"></div>

                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="#" target="_blank" rel="noopener"
                       class="btn-icon">
                
                        <span class="nav-link-inner--text">Business</span>
                    </a>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="#" target="_blank" rel="noopener"
                       class="btn-icon">
                
                        <span class="nav-link-inner--text">About</span>
                    </a>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <span class="span-111"></span>
                    <a href="#" target="_blank" rel="noopener"
                       class="btn-icon">
                
                        <span class="nav-link-inner--text">Pricing</span>
                    </a>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="#" target="_blank" rel="noopener"
                       class="btn-icon">
                
                        <span class="nav-link-inner--text">FAQ</span>
                    </a>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="#" target="_blank" rel="noopener"
                       class="btn-icon">
                
                        <span class="nav-link-inner--text">Contact Us</span>
                    </a>
                </li>
                
            </ul>
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
               
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="#" target="_blank" rel="noopener"
                       class="btn btn-neutral btn-icon">
               
                        <span class="nav-link-inner--text">Login</span>
                    </a>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="#" target="_blank" rel="noopener"
                       class="btn btn-neutral btn-icon">
                
                        <span class="nav-link-inner--text">Join now</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
