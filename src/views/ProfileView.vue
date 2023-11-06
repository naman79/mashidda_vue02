<template>
    <div class="profile">
        <font-awesome-icon icon="user" />
        <ProfileComponent msg="Welcome to MASHIDDA App"/>
    </div>
  </template>

<script>
// @ is an alias to /src
import ProfileComponent from '@/components/ProfileComponent.vue'

export default {
  name: 'ProfileView',
  components: {
    ProfileComponent
  }
}
</script>