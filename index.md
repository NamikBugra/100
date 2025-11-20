<style>
  body {
    margin: 0;
    overflow: hidden;
    background: #ffffff;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  }

  .emoji {
    position: fixed;
    top: -10vh;
    font-size: 40px;
    animation: fall 8s linear infinite;
    opacity: 0.9;
    pointer-events: none;
  }

  @keyframes fall {
    0% {
      transform: translateY(-10vh) rotate(0deg);
      opacity: 1;
    }
    100% {
      transform: translateY(110vh) rotate(360deg);
      opacity: 0;
    }
  }

  .main {
    position: relative;
    z-index: 10;
    text-align: center;
    margin-top: 30vh;
    padding: 0 20px;
  }

  .main h1 {
    font-size: 60px;
    margin-bottom: 10px;
  }

  .main p {
    font-size: 24px;
  }
</style>

<!-- Uçuşan emojiler -->
<div class="emoji" style="left: 5%;  animation-delay: 0s; ">💯</div>
<div class="emoji" style="left: 15%; animation-delay: 1s; ">💯</div>
<div class="emoji" style="left: 25%; animation-delay: 2s; ">💯</div>
<div class="emoji" style="left: 35%; animation-delay: 3s; ">💯</div>
<div class="emoji" style="left: 45%; animation-delay: 4s; ">💯</div>
<div class="emoji" style="left: 55%; animation-delay: 1.5s;">💯</div>
<div class="emoji" style="left: 65%; animation-delay: 2.5s;">💯</div>
<div class="emoji" style="left: 75%; animation-delay: 3.5s;">💯</div>
<div class="emoji" style="left: 85%; animation-delay: 0.5s;">💯</div>
<div class="emoji" style="left: 95%; animation-delay: 2.2s;">💯</div>

<!-- Asıl yazın -->
<div class="main">
  <h1>🎉 İyi ki doğdun! 🎉</h1>
  <p>Bu sayfa sadece senin için hazırlandı 💯🎂✨</p>
</div>
