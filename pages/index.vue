<template>
  <div>
    <h1 class="red">Red</h1>
    <Green>Green</Green>
  </div>
</template>

<script>
import styled from 'vue-styled-components'

const Green = styled.h1`
  color: green;
`

export default {
  components: {
    Green
  }
}
</script>

<style>
.red
{
  color: red;
}
</style>
