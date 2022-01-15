<template>
  <Tutorial v-bind:data="getObjects.objects" />
</template>

<script>
import getObjects from '../apollo/queries/posts.gql'
export default {
  apollo: {
    getObjects: {
      prefetch: true,
      query: getObjects
    }
  }
}
</script>
