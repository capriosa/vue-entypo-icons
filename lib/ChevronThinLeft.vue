<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M13.891,17.418c0.268,0.272,0.268,0.709,0,0.979c-0.268,0.27-0.701,0.271-0.969,0l-7.83-7.908
	c-0.268-0.27-0.268-0.707,0-0.979l7.83-7.908c0.268-0.27,0.701-0.27,0.969,0c0.268,0.271,0.268,0.709,0,0.979L6.75,10L13.891,17.418
	z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

