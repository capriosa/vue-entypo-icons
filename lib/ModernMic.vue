<template>
<div class="icon" :class="{'iborder':IconBorder }" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30">
      <path d="M1.228,10.891c-0.221,0.148-0.292,0.46-0.159,0.69l1.296,2.244c0.133,0.23,0.438,0.325,0.677,0.208L7,12.116V19h2v-7.854
	l4.071-1.973l-2.62-4.54L1.228,10.891z M18.457,3.037c-1.121-1.94-3.604-2.605-5.546-1.484c-0.91,0.525-1.508,1.359-1.801,2.289
	l2.976,5.156c0.951,0.212,1.973,0.11,2.885-0.415C18.913,7.462,19.578,4.98,18.457,3.037z"/></svg>
</div>

</template>

<script>
export default {
  props: {
  IconBorder: Boolean
}
}
</script>

