<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Xbox Russia</title>

  <!-- Стили Waline -->
  <link
    rel="stylesheet"
    href="https://unpkg.com/@waline/client@latest/dist/waline.css"
  />

  <style>
    .wl-count { visibility: hidden; }
    .wl-sort { visibility: hidden; }
    
    /* ваши стили тёмной темы */
    darkmode-selector {
      --waline-white: #000;
    }
  </style>
</head>

<body>
  <!-- Контент страницы -->

  <!-- Контейнер комментариев -->
  <div id="waline"></div>

  <!-- Скрипт Waline -->
  <script type="module">
    import { init } from 'https://unpkg.com/@waline/client@latest/dist/waline.js';

    init({
      el: '#waline',
      serverURL: 'https://commentxbox.vercel.app',
      path: '/Xbox-Russia/',
      lang: 'ru',
      reaction: false,
    });
  </script>
</body>
</html>
