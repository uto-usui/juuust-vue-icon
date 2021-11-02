<template>
  <svg
    xmlns="http://www.w3.org/2000/svg" :width="size" :height="size" viewBox="0 0 24 24" aria-hidden="true" v-on="$listeners" :fill="color"
  >
    <path d="M19.77 5.03l1.4 1.4L8.43 19.17l-5.6-5.6 1.4-1.4 4.2 4.2L19.77 5.03zm0-2.83L8.43 13.54l-4.2-4.2L0 13.57 8.43 22 24 6.43 19.77 2.2z"></path>
  </svg>
</template>
<script>
  export default {
    name: "IconDoneOutline",
    props: {
      size: {
        type: Number,
        default: 16
      },
      color: {
        type: String,
        default: "currentColor"
      }
    }
  };
</script>
