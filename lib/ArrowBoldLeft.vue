<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M10,2.5V6h7v8h-7v3.5L2.5,10L10,2.5z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

