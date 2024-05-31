<head>
  <center>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Full Page Box</title>
<style>
  body, html {
    margin: 0;
    padding: 0;
    height: 100%;
  }
  </center>
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
