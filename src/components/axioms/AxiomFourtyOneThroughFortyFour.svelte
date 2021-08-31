<script type="ts">
  import Typewriter from 'svelte-typewriter';
  import LoopDecode from '../effects/LoopDecode.svelte';

  let showFrom = false
</script>

<Typewriter cascade interval={20} on:done={() => showFrom = true}>
  <br />
  <ol>
    <li>
      <span>41. <span class="text-delta-green">Không được phép dùng Huyền, Đạo Thuật hay thứ giống phép thuật.</span></span>
      <br />
      <span class="pl-6">  <span class="text-delta-green">Ngươi sẽ không khác gì kẻ địch ngươi cần tiêu diệt.</span> </span>
      <br />
      <span class="pl-6">  Tập trung giải quyết vấn đề bằng các phương pháp khác trước khi siêu nhiên là giải pháp cuối. </span>
      <br />
      <span class="pl-6">  Nếu ngươi dùng giải pháp siêu nhiên, báo cáo với Trưởng Lão Hội. </span>
      <br />
      <span class="pl-6">  Còn đỡ hơn là để họ phát hiện ra ngươi làm điều đó và giấu họ. </span>
    </li>
    <br />
    <li>
      <span>42. <span class="text-delta-green">Không bao giờ bỏ lại đồng đội nơi chính phủ có thể tìm được.</span></span>
    </li>
    <br />
    <li>
      <span>43. <span class="text-delta-green">Luôn luôn báo cáo cho Trưởng Lão Hội.</span></span>
      <br />
      <span class="pl-6">  Kể cả khi điều đó khiến cho đồng đội ngươi <span class="text-delta-green">tử vong</span>. </span>
    </li>
    <br />
    <li>
      <span>44. <span class="text-delta-green">Nếu ngươi thành công, không cần giải thích hành động với Trưởng Lão Hội.</span></span>
      <br />
      <span class="pl-6">  Trưởng Lão Hội là người phán quyết cuối cùng đối với <span class="text-delta-green">thành công của ngươi</span>. </span>
    </li>
  </ol>
  <br />
  <br />
</Typewriter>

{#if showFrom}
--<LoopDecode />
{/if}
