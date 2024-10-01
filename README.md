# Hola! soy Nicolás

```html
<p align="center">
  <span id="changing-text">Hola! soy</span> Nicolás
</p>

<script>
  const phrases = [
    "Hola! soy",      // Español
    "Hello! I am",    // Inglés
    "你好! 我是",     // Chino Mandarín
    "Bonjour! je suis",  // Francés
    "Olá! eu sou"     // Portugués
  ];

  let index = 0;
  const changingText = document.getElementById('changing-text');

  setInterval(() => {
    changingText.textContent = phrases[index];
    index = (index + 1) % phrases.length;
  }, 2000); // Cambia cada 2 segundos
</script>
