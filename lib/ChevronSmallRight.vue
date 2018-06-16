<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M11,10L7.859,6.58c-0.268-0.27-0.268-0.707,0-0.978c0.268-0.27,0.701-0.27,0.969,0l3.83,3.908
	c0.268,0.271,0.268,0.709,0,0.979l-3.83,3.908c-0.267,0.272-0.701,0.27-0.969,0c-0.268-0.269-0.268-0.707,0-0.978L11,10z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

