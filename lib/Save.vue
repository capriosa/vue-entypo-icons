<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M15.173,2H4C2.899,2,2,2.9,2,4v12c0,1.1,0.899,2,2,2h12c1.101,0,2-0.9,2-2V5.127L15.173,2z M14,8c0,0.549-0.45,1-1,1H7
	C6.45,9,6,8.549,6,8V3h8V8z M13,4h-2v4h2V4z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

