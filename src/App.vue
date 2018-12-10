<template>
  <div class="card">
    <a :href="link" target="_blank">
      <img src="https://commbocc.github.io/hc-btn-prc-adopt/public/adopt.jpg" alt="Adopt at Pet Resource Center's Online Kennel" class="card-img">
    </a>
    <div class="bg-secondary text-center p-3">
      <a :href="link" class="btn btn-warning btn-lg btn-wrap" target="_blank">
        <strong>
          Search Pet Resource Center's Online Kennel
        </strong>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    link: {
      type: String,
      default: 'https://public-solutions.hillsboroughcounty.org/enterprise/f?p=236:1::::::'
    }
  }
}
</script>

<style scoped src="./assets/main.scss" lang="scss"></style>
