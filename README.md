```html
<div style="color: green; font-family: monospace;">
  <p id="typing-animation"></p>
</div>

<style>
  @keyframes typing {
    from { width: 0; }
    to { width: 100%; }
  }

  #typing-animation::after {
    content: "Hey, I'm Sachu (TRASHZ403)";
    animation: typing 3s steps(28) infinite;
  }
</style>

