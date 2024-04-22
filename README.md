```html
<div style="color: green; font-family: monospace;">
  <p>Hey, I'm Sachu (TRASHZ403)</p>
  <p id="typing-animation"></p>
</div>

<script>
  const text = "Hey, I'm Sachu (TRASHZ403)";
  const typingAnimation = document.getElementById('typing-animation');
  let index = 0;

  function type() {
    if (index < text.length) {
      typingAnimation.innerHTML += text.charAt(index);
      index++;
      setTimeout(type, 100); // Adjust typing speed here (milliseconds)
    }
  }

  type();
</script>
