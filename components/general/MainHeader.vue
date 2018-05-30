<template>

  <header role="banner">

        <nav class="navbar main-navbar" role="navigation" aria-label="main navigation">
            <div class="navbar-brand">
                <router-link class="navbar-item" lang="en" to="/">Home</router-link>
                <router-link class="navbar-item" lang="en" to="/background">Background</router-link>
                <router-link class="navbar-item" lang="en" to="/events">Public Events</router-link>
                <router-link class="navbar-item" lang="en" to="/activities">Other Activities</router-link>
                <router-link class="navbar-item" lang="en" to="/blog">Blogs &amp; Other Coverage</router-link>
                <router-link class="navbar-item" lang="en" to="/participate">Participate</router-link>
                <router-link class="navbar-item" lang="en" to="/gaadlogo">Download GAAD Logo</router-link>
                <router-link class="navbar-item" lang="en" to="/contact">Contact</router-link>
                <a class="navbar-item" lang="en" href="http://www.facebook.com/globalaccessibilityawarenessday" aria-label="Facebook"><i class="fa fa-facebook" aria-hidden="true"></i></a>
                <a class="navbar-item" lang="en" href="http://www.twitter.com/gbla11yday" aria-label="Twitter"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                <a class="navbar-item" lang="en" href="https://www.youtube.com/user/gbla11yawarenessday" aria-label="YouTube"><i class="fa fa-youtube" aria-hidden="true"></i></a>
                <a class="navbar-item" lang="en" href="http://pinterest.com/pin/341147740493704922/" aria-label="Pinterest"><i class="fa fa-pinterest-p" aria-hidden="true"></i></a>

              <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
              </a>
            </div>
        </nav>   
  </header>

</template>



<script>

</script>



<style lang="scss" scoped>

.main-navbar a {
  transition: all 0.5s ease;
    &:hover {
      color: hsl(197.6°, 100, 27.5) !important;
      background-color: #FFF;
  }
}
header {
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 1000;
}

nav {

  background: #666;
  font-size: 1.2rem;

  .navbar-brand {
    margin: 0 auto;
  }

  .navbar-item {
    color: #FFF;
    height: 5rem;
  }

}


</style>