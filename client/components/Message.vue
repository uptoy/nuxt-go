<template>
  <div class="message">
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  name: 'Message',
  // props: ['message']
  props: {
    message: {
      type: String,
      required: true,
      default: 'ハロー！',
    }
  },
}
</script>

