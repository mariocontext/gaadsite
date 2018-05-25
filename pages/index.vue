<template>
  <span>
    <h1 class="is-size-1 has-text-centered">Global Accessibility Awareness Day</h1>
    <h2 class="is-size-2 has-text-centered">MAY 17 2018</h2>
    <section class="box">
      <p>Join us on Thursday, May 17 2018 and mark the seventh Global Accessibility Awareness Day (GAAD). The purpose of GAAD is to get everyone talking, thinking and learning about digital (web, software, mobile, etc.) access/inclusion and people with different disabilities.</p>
    </section>
    <section class="section">
      <p>
        The target audience of GAAD is the design, development, usability, and related communities who build, shape, fund and influence technology and its use. While people may be interested in the topic of making technology accessible and usable by persons with disabilities, the reality is that they often do not know how or where to start. Awareness comes first. Read <a href="http://mysqltalk.wordpress.com/2011/11/27/challenge-accessibility-know-how-needs-to-go-mainstream-with-developers-now">blog post by Joe Devon</a> that inspired GAAD.
      </p>
    </section>
    <section class="section">
      <h3>Learn more about</h3>
					<ul>
						<li><router-link to="/background">How this all got started</router-link></li>
						<li><router-link to="/events">Public events that you are invited to attend</router-link></li>
						<li><router-link to="/activities">Other activities taking place to mark the day</router-link></li>
					</ul>

					<p>Whether you participate in an organized activity with others or not, join us and take an hour out of your day to <router-link to="/participate">experience digital accessibility first-hand</router-link>.</p>
					<ul class="no-list-style">

						<li>
              <span class="icon is-medium">
                <i class="fas fa-envelope"></i>
              </span>
              E-mail us at <a href="mailto:globala11yawarenessday@gmail.com">globala11yawarenessday at gmail.com</a>.</li>

						<li> 
              <span class="icon is-medium">
                <i class="fas fa-facebook"></i>
              </span>
              Show support for this effort by <a href="https://www.facebook.com/globalaccessibilityawarenessday">Liking our Facebook page</a>.</li>
						<li>
              <span class="icon is-medium">
                <i class="fas fa-twitter"></i>
              </span>
              <a href="https://twitter.com/gbla11yday">Follow gbla11yday on Twitter</a> and tweet using the #gaad hashtag.</li>
					</ul>
					<div class="callout">
            <span class="icon is-medium">
                <i class="fas fa-mic"></i>
              </span>
            <a href="http://www.webaxe.org/">Webaxe</a> has generously <a href="http://www.webaxe.org/podcast-95-global-accessibility-awareness-day-surveys-more/">interviewed us</a> for this podcast!</div>
					<h3>Information on GAAD is available in:</h3>
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
   
    data:function() {
    
      return {
        message: 'hello from data!',
        seen: true,
        todos: [
          { id:1, text: 'Learn JavaScript' },
          { id: 2, text: 'Learn Vue' },
          { id: 3, text: 'Build something awesome' }
        ]
        
      }
    }
    
  }

</script>

<style scoped>
  
</style>
