<script type="ts">
  import Typewriter from 'svelte-typewriter';
  export let onFinish;
</script>


<Typewriter interval={80} on:done={onFinish}>
  <h3 class="text-2xl times24">Tải dữ liệu...</h3>
</Typewriter>
