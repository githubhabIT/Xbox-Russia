<head>
  <link
    rel="stylesheet"
    href="https://unpkg.com/@waline/client@v3/dist/waline.css"
  />
</head>
<body>
  <!-- ... -->
  <div id="waline"></div>
  <script type="module">
    import { init } from 'https://unpkg.com/@waline/client@v3/dist/waline.js';

    init({
      el: '#waline',
      serverURL: 'https://commentxbox.vercel.app',
      lang: 'ru',
    });
  </script>
</body>
<style>
.wl-count { visibility: hidden; }
.wl-sort { visibility: hidden; }
.container-lg { visibility: hidden; }
</style>
