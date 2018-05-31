<template>
  <span>
    <div class="logo-area">
      <img src="~/assets/images/gaad-logo-greyscale.png" alt="Global Accessibility Awareness Day logo showing the letters GAAD encircled by a graphic of a keyboard and wire ">
    </div>
      <h1 class="is-size-1 has-text-centered">Global Accessibility Awareness Day</h1>
      <section class="box">
        <h2>May 17, 2018 is the day!</h2>
        <p>Join us on Thursday, May 17 2018 and mark the seventh Global Accessibility Awareness Day (GAAD). The purpose of GAAD is to get everyone talking, thinking and learning about digital (web, software, mobile, etc.) access/inclusion and people with different disabilities.</p>
        <p>
          The target audience of GAAD is the design, development, usability, and related communities who build, shape, fund and influence technology and its use. While people may be interested in the topic of making technology accessible and usable by persons with disabilities, the reality is that they often do not know how or where to start. Awareness comes first. Read <a href="http://mysqltalk.wordpress.com/2011/11/27/challenge-accessibility-know-how-needs-to-go-mainstream-with-developers-now">blog post by Joe Devon</a> that inspired GAAD.
        </p>
    </section>

      <section>
      <h2>Learn more about</h2>
					<ul>
						<li><router-link to="/background">How this all got started</router-link></li>
						<li><router-link to="/events">Public events that you are invited to attend</router-link></li>
						<li><router-link to="/activities">Other activities taking place to mark the day</router-link></li>
					</ul>

      <h2>Interact</h2>
					<p>Whether you participate in an organized activity with others or not, join us and take an hour out of your day to <router-link to="/participate">experience digital accessibility first-hand</router-link>.</p>

					<ul class="no-list-style">

						<li>
              <span class="icon is-medium">
                <i class="fa fa-envelope"></i>
              </span>
              E-mail us at <a href="mailto:globala11yawarenessday@gmail.com">globala11yawarenessday at gmail.com</a>.</li>

						<li> 
              <span class="icon is-medium">
                <i class="fa fa-facebook"></i>
              </span>
              Show support for this effort by <a href="https://www.facebook.com/globalaccessibilityawarenessday">Liking our Facebook page</a>.</li>
						<li>
              <span class="icon is-medium">
                <i class="fa fa-twitter"></i>
              </span>
              <a href="https://twitter.com/gbla11yday">Follow gbla11yday on Twitter</a> and tweet using the #gaad hashtag.</li>
					</ul>
					<div class="callout">
            <span class="icon is-medium">
                <i class="fa fa-microphone"></i>
              </span>
            <a href="http://www.webaxe.org/">Webaxe</a> has generously <a href="http://www.webaxe.org/podcast-95-global-accessibility-awareness-day-surveys-more/">interviewed us</a> for this podcast!</div>

					<h2>Information on GAAD is available in:</h2>
					<ul>
						<li><a lang="es" href="#">español</a></li>
						<li><a lang="fr" href="#">Français</a></li>
						<li><a lang="ja" href="#">日本語</a></li>
						<li><a lang="ru" href="#">русский</a></li>
						<li><a lang="pt-BR" href="#">português brasileiro</a></li>
					</ul>
    </section>

  </span>
</template>

<script>
  
  module.exports = {

    layout: 'singlecol',
    
  }

</script>

<style scoped>

.logo-area {
  text-align: center;
}
  
</style>
