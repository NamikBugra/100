<style>
  body {
    overflow: hidden;
    margin: 0;
    background: #ffffff;
  }

  .emoji {
    position: fixed;
    top: -50px;
    font-size: 40px;
    animation: fall linear infinite;
    pointer-events: none;
  }

  @keyframes fall {
    0% {
      transform: translateY(-50px) rotate(0deg);
      opacity: 1;
    }
    100% {
      transform: translateY(110vh) rotate(360deg);
      opacity: 0;
    }
  }
</style>

<script>
  const emojis = ["💯", "💯", "💯", "💯"]; // istersen buraya başka emojiler de ekleyebilirsin

  function createEmoji() {
    const emoji = document.createElement("div");
    emoji.classList.add("emoji");
    emo
