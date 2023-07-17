<script setup>
import WelcomeItem from './LinkItems.vue'
import GithubIcon from './icons/IconGithub.vue'
import LinkedinIcon from './icons/IconLinkedIn.vue'
import GpnIcon from './icons/IconGpn.vue'
import ContactIcon from './icons/IconContact.vue'
import MediumIcon from './icons/IconMedium.vue'

</script>

<template>
  <WelcomeItem>
    <template #icon>
      <GithubIcon />
    </template>
    <template #heading>Github</template>

    Code, commits and chaos can be found at
    <a href="https://github.com/bellalaf" target="_blank" rel="noopener">github.com/bellalaf</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <LinkedinIcon />
    </template>
    <template #heading>LinkedIn</template>

    Go on, have a stalk.
    <a href="https://www.linkedin.com/in/bella-lafrenais/" target="_blank" rel="noopener">in/bella-lafrenais</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <MediumIcon />
    </template>
    <template #heading>Medium</template>

    My deep dark thoughts on Reactive Programming await...
    <a href="https://medium.com/@bella.lafrenais" target="_blank" rel="noopener">medium.com/@bella.lafrenais</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ContactIcon />
    </template>
    <template #heading>Contact</template>

    Email me at
    <a href="isabellalaf98@gmail.com" target="_blank" rel="noopener">isabellalaf98@gmail.com</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <GpnIcon />
    </template>
    <template #heading>GPN</template>

    Interested in what we're doing over at Girls Programming Network?
    <li>To volunteer in our Melbourne team, go to <a href="https://www.girlsprogramming.network/melbourne" target="_blank" rel="noopener">gpn/melbourne</a>.</li>
    <li>To sign up a high school student for the next event, go to <a href="https://eng.unimelb.edu.au/engage-with-us/schools/gpn" target="_blank" rel="noopener">unimelb/gpn</a>.</li>
    <li>Want to be involved at a larger scale? <a href="https://www.techinclusion.org.au/sponsor-us" target="_blank" rel="noopener">Sponsor us</a>.</li>
    Just want to chat or have questions about GPN? Contact me via details above 😄

  </WelcomeItem>

</template>
