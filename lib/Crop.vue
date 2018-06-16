<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M6,14V1H4v3H1v2h3v8c0,1.0996094,0.8989258,2,2,2h8v3h2v-3h3v-2H6z M14,13h2V6c0-1.0996094-0.8989258-2-2-2H7v2h7V13z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

