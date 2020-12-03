<template lang='pug'>
.projects
  h2.title PERSONNAL PROJECTS
  p.subtitle.mb-6
    | During the last 4 years, I've been working on a lot of personal projects.
    | A bunch of them never came to fruition but are still partly available online.
    | You can see them on my #[a(href="http://github.com/sylver-john") github profile].
  .block.mb-6
    h3.has-text-centered.is-size-3.mb-4 Pulsar
    p.has-text-centered.mb-5
      | Pulsar is a working group that I set up with a friend in 2016.
      | Our objective is to develop personal projects with each time
      | a technology that we do not master in order to increase our skills.
      | We are today a team of 4 and you can find us on our website #[a(href="http://pulsar.surge.sh") http://pulsar.surge.sh]
    .columns.has-text-centered
      .column
        h4.is-size-4 #[a(href="https://mmorainville.github.io/netsix-gh-pages/") Netsix]
        p.subtitle It's an application made with Electron and VueJs: we use WebRTC to share streaming videos between two clients.
      .column
        h4.is-size-4 #[a(href="https://pulsardev.github.io/mendelable/") Mendelable]
        p.subtitle We love science so we made a beautiful periodic table with VueJs and Bulma
      .column
        h4.is-size-4 #[a(href="https://freatle.com/") Freatle]
        p.subtitle My favorite: an application that allows you to organize an event and to know who brings what.
          | First made with Bulma, VueJs and Graphcool, we have completely redesigned it to include Tailwind and Strapi.
  .block
    h3.has-text-centered.is-size-3.mb-4 Personal works
    p.has-text-centered.mb-5
      | These are my main personal projects. They are not available on Github (I'm keeping them privet but I can show you them on demand)
    .columns.has-text-centered
      .column
        h4.is-size-4 Newcomer [WIP]
        p.subtitle It's an onbarding SaaS application made with VueJs, Bulma and Strapi (REST mode)
      .column
        h4.is-size-4 AskNurse [WIP]
        p.subtitle Here in France we have a problem with our medical system, in particular with our emergency system.
          | AskNurse is an applicatio where poeple can ask help before going to the hospital.
      .column
        h4.is-size-4 #[a(href="https://medium.com/@pulsar.dev.team") Blog articles]
        p.subtitle I written several articles about my personal projects.
</template>

<script>
export default {
  name: 'Projects'
}
</script>

<style>
</style>
