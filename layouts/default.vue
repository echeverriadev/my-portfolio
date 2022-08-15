<template>
  <b-container>
    <b-row align-h="center">
      <b-col>
        <Profile />
        <Nuxt />
      </b-col>
    </b-row>
  </b-container>
</template>

<script lang="ts">
import Profile from '@/components/shared/profile/index.vue'

export default {
  components: {
    Profile,
  },
}
</script>
