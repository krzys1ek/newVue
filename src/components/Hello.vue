<template lang="html">
<div class="kolor">
  {{ message }}
</div>
</template>

<script>
export default {
  data() {
    return {
      message: 'BOOM'
    }
  }
}
</script>

<style lang="css">
$color: red;
.kolor {
  color: $color;
}
</style>
