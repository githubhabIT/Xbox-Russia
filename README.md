<head>
  <!-- ... -->
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
      serverURL: 'https://commentxbox.vercel.app/',
      lang: 'ru',
      reaction: '', // Set reaction to an empty string
    });
  </script>
</body>
<style>
.wl-count { visibility: hidden; }
.wl-sort { visibility: hidden; }
  darkmode-selector {
  /* Regular color */
  --waline-white: #000;
</style>
