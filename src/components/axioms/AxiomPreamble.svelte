<script type="ts">
  import Typewriter from 'svelte-typewriter';
  export let onFinish;
</script>

<Typewriter cascade on:done={onFinish}>
  <br />
  <p> Đây là mấy cái <span class="text-delta-green">"Trấn Vũ Chỉ Lệnh"</span> mà vẫn hay nhắc tới. </p>
  <br />
  <span> tôi chịu không biết là có đúng là nó thật sự viết bởi <span class="text-delta-green">Trịnh Gia</span>.</span>
  <br />
  <span> Viết ra mấy cái này không giống kiểu của ông già đó lắm..</span>
  <br />
  <span> Có lẽ là lão thấy cần thay đổi theo thời gian, và chúng ta góp thêm vào?</span>
  <br />
  <p>Ai mà biết được qua hàng trăm năm đã thêm bao nhiêu điều mới rồi?</p>
  <br />
  <span> Đừng quá lo nếu như ngươi không thuộc hết. </span>
  <br />
  <p> Nó là một bộ chỉ lệnh cho thành viên <span class="text-delta-green">Trấn Vũ Hội</span> khi ra ngoài thực địa.</p>
  <br />
  <span class="text-delta-green">Nếu tóm gọn, thì nó vẫn là:</span>
  <ul>
    <li> Tìm kiếm mối nguy </li>
    <li> Ngăn chặn mối nguy </li>
    <li> Che đậy như thể mối nguy đó chưa bao giờ xảy ra </li>
  </ul>
  <br />
</Typewriter>
