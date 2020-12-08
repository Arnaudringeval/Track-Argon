<template>
    <header class="header-global">
        <img id="logoa" src="img/header/logo_track.png" alt="">
        <div class="brand">
            <h1 id="titrea">TRACK</h1>
            <h2 class="namea">Touring Race All Competition's Keys</h2>
            <h3 id="h3"> </h3>
        </div>
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/">
                        <img src="img/brand/blue.png">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <base-dropdown class="nav-item" menu-classes="dropdown-menu-xl">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-ui-04 d-lg-none"></i>
                        <span class="nav-link-inner--text">Components</span>
                    </a>
                    <div class="dropdown-menu-inner">
                        <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-primary rounded-circle text-white">
                                <i class="ni ni-spaceship"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="heading text-primary mb-md-1">Getting started</h6>
                                <p class="description d-none d-md-inline-block mb-0">Get started with Bootstrap, the
                                    world's most popular framework for building responsive sites.</p>
                            </div>
                        </a>
                        <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                                <i class="ni ni-ui-04"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-warning mb-md-1">Components</h5>
                                <p class="description d-none d-md-inline-block mb-0">Learn how to use Argon
                                    compiling Scss, change brand colors and more.</p>
                            </div>
                        </a>
                    </div>
                </base-dropdown>
                <base-dropdown tag="li" class="nav-item">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-collection d-lg-none"></i>
                        <span class="nav-link-inner--text">Examples</span>
                    </a>
                    <router-link to="/landing" class="dropdown-item">Landing</router-link>
                    <router-link to="/profile" class="dropdown-item">Profile</router-link>
                    <router-link to="/login" class="dropdown-item">Login</router-link>
                    <router-link to="/register" class="dropdown-item">Register</router-link>
                </base-dropdown>
            </ul>
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://www.facebook.com/creativetim" target="_blank" rel="noopener"
                       data-toggle="tooltip" title="Like us on Facebook">
                        <i class="fa fa-facebook-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Facebook</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://www.instagram.com/creativetimofficial"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="Follow us on Instagram">
                        <i class="fa fa-instagram"></i>
                        <span class="nav-link-inner--text d-lg-none">Instagram</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://twitter.com/creativetim" target="_blank" rel="noopener"
                       data-toggle="tooltip" title="Follow us on Twitter">
                        <i class="fa fa-twitter-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Twitter</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://github.com/creativetimofficial/vue-argon-design-system"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="Star us on Github">
                        <i class="fa fa-github"></i>
                        <span class="nav-link-inner--text d-lg-none">Github</span>
                    </a>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="https://www.creative-tim.com/product/vue-argon-design-system" target="_blank" rel="noopener"
                       class="btn btn-neutral btn-icon">
                <span class="btn-inner--icon">
                  <i class="fa fa-cloud-download mr-2"></i>
                </span>
                        <span class="nav-link-inner--text">Download</span>
                    </a>
                </li>
            </ul>
        </base-nav>

<ul id="menus">
            <li>les bases
                <ul>
                    <li><a href="motorisation.html">motorisation</a></li>
                    <li><a href="transmission.html">transmission</a></li>
                    <li><a href="pneus.html">pneus</a></li>
                    <li><a href="carrosseries.html">carrosseries</a></li>
                    <li><a href="reglages.html">réglages</a></li>
                </ul>
            </li>
            <li id="regl">réglements
                <ul id="réglements">
                    <li id="ffvrc"><a href="https://www.ffvrc.fr/fr/disciplines-sur-piste/1-10-1-12-electrique-piste/356-rglt.html" target="_blank">FFVRC</a></li>
                    <li><a href="https://www.efra.ws/handbook/" target="_blank">EFRA</a></li>
                    <li><a href="https://ets.redrc.net/rules/" target="_blank">ETS</a></li>
                    <li><a href="https://www.ifmar.org/rules/" target="_blank">IFMAR</a></li>
                </ul>
            </li>
            <li><a href="tutos.html">tutos</a>

            </li>
            <li>vidéos
                <ul>
                    <li><a href="championnatdumonde.html">Championnat du monde</a></li>
                    <li><a href="championnatdeurope.html">Chapionnat d'Europe</a></li>
                    <li><a href="ets.html">ETS</a></li>
                    <li><a href="autres.html">Autres</a></li>
                </ul>

            </li>
            <li><a href="calendrier.html">calendrier</a>

            </li>
        </ul>

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
.brand {
        text-align: center;
    }
#menus {
        display: none;
    }
header {
        display: flex;
        position: fixed;
        flex-direction: column-reverse;
        justify-content: center;
        background-color: #cdcdcd;
        padding: 0 0 0 0;
        z-index: 7;
        width: 100%;
    }
#logoa {
        align-self: center;
        width: 369px;
        height: 238px;
        margin-top: 0px;
        margin-left: 0px;
    }
#titrea {
        font-size: 75px;
        margin: 0px 0 0 0px;
        font-family: 'Arial black', Helvetica, sans-serif;
        font-style: italic;
        color: #318ce7;
    }
.namea{
    display: none;
    color: #318ce7;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 35px;
    padding: -5px 0 0 5px;
    font-weight: bold;
    }
    @media screen and (min-width: 690px) and (max-width: 992px){
        .namea {
            display: block;}
        header {
            display: flex;
            flex-direction: row;
        }
}
@media screen and (min-width: 992px) {
.navbar-main{
    display: none;
}


#menus {
            display: flex;
            justify-content: space-between;
            text-align: center;
            margin: 0 0 0 0;
            left: 10%;
            right: 0;
            font-family: Arial, Helvetica, sans-serif;
            position: fixed;
            padding: 0 0 0 0;
            width: 80%;
            background-color: #cdcdcd;
        }
        #menus ul {
            position: absolute;
            display: none;
            left: 0;
            z-index: 1000;
        }
        #menus,
        #menus ul {
            list-style: none;
            text-align: center;
        }
        #menus li {
            display: inline-block;
            background-color: #318ce7;
            padding: 5px 0 5px 0;
            color: #ffffff;
            font-weight: bold;
            width: 110px;
        }
        #menus ul li:first-child {
            margin-top: 5px;
        }
        #menus ul li:last-child {
            border-radius: 0 0 8px 8px;
        }
        #menus li {
            display: inline-block;
            position: relative;
            border-radius: 8px 8px 0 0;
        }
        #menus ul li {
            display: inherit;
            text-align: center;
            border-radius: 0;
        }
        #menus li:hover ul {
            display: block;
        }
        #menus a {
            text-decoration: none;
            display: block;
            color: #ffffff;
        }
        #menus li ul {
            text-align: center;
        }
        #menus li li a {
            font-weight: normal;
        }
        #menus li li:hover a {
            font-style: italic;
            text-transform: inherit;
            font-weight: normal;
        }
}
</style>
