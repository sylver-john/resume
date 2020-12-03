<template lang='pug'>
div.has-background-light
  .container.pt-6
    .columns
      .column.is-3.has-background-grey-lighter
        .block
          figure.image.is-256x256
            img(src='/images/sylver.jpg')
        .block
          Personnal
        .block
          Interests
      .column
        section.section
          .container
            h1.title Web Developer
            p Passionate and interested. These are for me the most important qualities to be a good developer,
              | not a perfect developer but #[strong a good developer], with a taste for learning, challenge and a critical
              | mind developed enough to be able to choose judiciously the solutions to the problems encountered.
              | With almost 6 years of professional experience and 4 years of personal project,
              | I learn new things every week in order to improve my skills and to be able to express my potential and creativity.
        hr.has-background-grey-dark
        section.section
          .container
            Experiences
        hr.has-background-grey-dark
        section.section
          .container
            Projects
        hr.has-background-grey-dark
        section.section
          .container
            Skills
        hr.has-background-grey-dark
        section.section
          .container
            Degrees
</template>
<script>
import Personnal from '~/components/PersonnalInfo'
import Interests from '~/components/Interests'
import Experiences from '~/components/Experiences'
import Projects from '~/components/Projects'
import Skills from '~/components/Skills'
import Degrees from '~/components/Degrees'

export default {
  components: {
    Personnal,
    Interests,
    Experiences,
    Projects,
    Skills,
    Degrees
  }
}
</script>

<style>
</style>
