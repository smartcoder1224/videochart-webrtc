<!-- Copyright (c) 2020-2021 Dev Mastery -->

<template>
  <i class="f7" :data-f7-icon="name" aria-hidden="true" />
</template>

<script>
export default {
  name: "sea-symbol",
  props: {
    name: {
      type: String,
      default: 0,
      required: true,
    },
  },
}
</script>
