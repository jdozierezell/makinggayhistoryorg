<template>
  <div class="container container--narrow content-page">
    <h1>{{ heading }}</h1>
    <div class="flexbox">
      <img src="~assets/img/IMG_4119.jpg" :alt="imageAlt">
      <p v-html="body"></p>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      heading: 'Events',
      imageAlt: 'Photo of group with Eric Marus at Trevor Project presentation',
      body: 'Making Gay History produces exciting and engaging panel discussions, listening parties, and live events, including Making Gay History’s Queer Quiz Show®, an interactive gay history trivia contest.  We’ve presented to schools, companies, community groups, and organizations of all kinds.<br /><br /><a href="mailto:carol@workman.com">Contact Carol Schneider</a> for information.'
    }
  },
  transition: 'fade'
}
</script>
