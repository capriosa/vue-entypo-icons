<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M17,8H5.021l8.974-5.265L13,1L1.736,7.571C1.28,7.837,1,8.324,1,8.852V17c0,1.105,0.895,2,2,2h14c1.105,0,2-0.895,2-2v-7
	C19,8.895,18.105,8,17,8z M15.5,17c-0.828,0-1.5-0.672-1.5-1.5c0-0.828,0.672-1.5,1.5-1.5s1.5,0.672,1.5,1.5
	C17,16.328,16.328,17,15.5,17z M17,12H3v-2h14V12z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

