<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M12.244,9.52L5.041,4.571C4.469,4.188,4,4.469,4,5.196v9.609c0,0.725,0.469,1.006,1.041,0.625l7.203-4.951
	c0,0,0.279-0.199,0.279-0.478C12.523,9.721,12.244,9.52,12.244,9.52z M14,4h1c0.553,0,1,0.048,1,0.6V15.4c0,0.552-0.447,0.6-1,0.6
	h-1c-0.553,0-1-0.048-1-0.6V4.6C13,4.048,13.447,4,14,4z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

