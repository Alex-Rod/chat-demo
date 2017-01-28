<template lang="html">
  <div class="chat-log">
    <chat-message></chat-message>
    <chat-message></chat-message>
    <chat-message></chat-message>
  </div>
</template>

<script>
  export default {
    data() {
      {
        messages: [
          message: "hey"
        ]
      }
    }
  }
</script>

<style lang="css">
.chat-log .chat-message:nth-child(even){
  background-color: #ccc;
}
</style>
