<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M19,3H1C0.448,3,0,3.447,0,4v12c0,0.553,0.448,1,1,1h18c0.552,0,1-0.447,1-1V4C20,3.447,19.553,3,19,3z M18,15H2V5h16V15z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

