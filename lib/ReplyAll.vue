<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M7.225,5.767V3.086L0,9.542l7.225,6.691v-2.777L3,9.542L7.225,5.767z M12.225,6.953V3.086L5,9.542l7.225,6.691v-4.357
	c3.292,0,5.291,0.422,7.775,4.81C20,16.685,19.632,6.953,12.225,6.953z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

