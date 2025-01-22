<body>
  <p id="comments-loading-message">Отзывы отображаются снизу, дождитесь загрузки</p>
  <div id="waline"></div>
  <script type="module">
    import { init } from 'https://unpkg.com/@waline/client@v3/dist/waline.js';

    init({
      el: '#waline',
      serverURL: 'https://commentxbox.vercel.app/',
      lang: 'ru',
      reaction: false,
    });
  </script>
</body>
<style>
.wl-count { visibility: hidden; }
.wl-sort { visibility: hidden; }
darkmode-selector {
  --waline-white: #000;
}
/* Скрываем сообщение после загрузки Waline */
#waline.loaded + #comments-loading-message {
    display: none;
}
</style>
