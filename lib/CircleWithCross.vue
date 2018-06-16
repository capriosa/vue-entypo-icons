<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M10,1.6c-4.639,0-8.4,3.761-8.4,8.4c0,4.639,3.761,8.4,8.4,8.4s8.4-3.761,8.4-8.4C18.4,5.361,14.639,1.6,10,1.6z
	 M14.789,13.061l-1.729,1.729L10,11.729l-3.061,3.06l-1.729-1.729L8.272,10L5.211,6.939L6.94,5.211L10,8.271l3.061-3.061
	l1.729,1.729L11.728,10L14.789,13.061z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

