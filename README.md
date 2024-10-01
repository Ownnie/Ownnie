# <h1 align="center">
  <span id="changing-text">Hola! soy</span> Nicolás
</h1>

<style>
  @keyframes changeText {
    0%   { content: "Hola! soy"; }
    20%  { content: "Hello! I am"; }
    40%  { content: "你好! 我是"; }
    60%  { content: "¡Hola! soy"; }
    80%  { content: "Bonjour! je suis"; }
    100% { content: "Olá! eu sou"; }
  }
  #changing-text::after {
    animation: changeText 10s infinite;
    content: "Hola! soy";
  }
</style>
