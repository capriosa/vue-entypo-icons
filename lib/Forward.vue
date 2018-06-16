<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M12,11.874v4.357l7-6.69l-7-6.572v3.983c-8.775,0-11,9.732-11,9.732C3.484,12.296,7.237,11.874,12,11.874z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

