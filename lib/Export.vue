<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M15,15H2V6h2.595c0,0,0.689-0.896,2.17-2H1C0.447,4,0,4.449,0,5v11c0,0.553,0.447,1,1,1h15c0.553,0,1-0.447,1-1v-3.746
	l-2,1.645V15z M13.361,8.05v3.551L20,6.4l-6.639-4.999v3.131C5.3,4.532,5.3,12.5,5.3,12.5C7.582,8.752,8.986,8.05,13.361,8.05z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

