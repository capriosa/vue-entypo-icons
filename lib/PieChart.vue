<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M11,0.958v9.039C11,10.551,10.551,11,9.997,11H0.958c0.498,4.555,4.355,8.1,9.042,8.1c5.026,0,9.1-4.074,9.1-9.1
	C19.1,5.312,15.555,1.456,11,0.958z M9,0.958C4.774,1.42,1.42,4.774,0.958,9H9V0.958z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

