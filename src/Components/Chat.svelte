<script>
  export let chat = ""
  export let from = "me"
</script>
{#if from == "bot"}
<div class="chat chat-start">
  <div class="chat-bubble">{chat}</div>
</div>
{:else}
<div class="chat chat-end">
  <div class="chat-bubble">{chat}</div>
</div>
{/if}