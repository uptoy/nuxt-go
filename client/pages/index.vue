<template>
  <div>
    <Tutorial />
    <Sample />
    <NuxtLogo />
    <Message :message="myMessage"></Message>
    <Message />
  </div>
</template>

<script>
import Message from '~/components/Message.vue';
import NuxtLogo from '~/components/NuxtLogo.vue';
import Sample from '~/components/Sample.vue';
import Tutorial from '~/components/Tutorial.vue';
export default {
  name: 'IndexPage',
  data() {
    return {
      myMessage: 'Hello Vue.js!aa'
    }
  },
  components: {
    Message: Message,
  },
}
</script>
