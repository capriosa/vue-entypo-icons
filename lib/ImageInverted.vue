<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M18,3H2C1.447,3,1,3.447,1,4v12c0,0.552,0.447,1,1,1h16c0.553,0,1-0.448,1-1V4C19,3.448,18.553,3,18,3z M13.25,6.5
	c0.69,0,1.25,0.56,1.25,1.25S13.94,9,13.25,9S12,8.44,12,7.75S12.56,6.5,13.25,6.5z M4,14l3.314-7.619l3.769,6.102l3.231-1.605
	L16,14H4z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

