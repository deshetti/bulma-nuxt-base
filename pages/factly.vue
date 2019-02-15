<template>
  <div>
    <hero />
    <about />
    <services />
    <resume />
    <portfolio />
    <contact />
  </div>
</template>

<script>
import Hero from '~/components/Hero'
import About from '~/components/About'
import Services from '~/components/Services'
import Resume from '~/components/Resume'
import Portfolio from '~/components/Portfolio'
import Contact from '~/components/Contact'

export default {
  name: 'HomePage',

  components: {
    Hero,
    About,
    Services,
    Resume,
    Portfolio,
    Contact
  }
}
</script>
