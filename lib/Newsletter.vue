<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M18,3H2C1.4472656,3,1,3.4472656,1,4v12c0,0.5517578,0.4472656,1,1,1h16c0.5527344,0,1-0.4482422,1-1V4
	C19,3.4481812,18.5527344,3,18,3z M4,10h6v1H4V10z M12,14H4v-1h8V14z M17,8h-3V5h3V8z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

