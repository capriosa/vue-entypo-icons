<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M16,1H4C3.447,1,3,1.447,3,2v16c0,0.552,0.447,1,1,1h12c0.553,0,1-0.448,1-1V2
	C17,1.448,16.553,1,16,1z M15,17H5V3h10V17z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

