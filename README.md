<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>OMplex AI</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
  <div class="logo">OM<span>plex</span></div>
  <div class="online">● Online</div>
</header>

<main>

  <section class="hero">
    <h1>Welcome to <span>OMplex</span> 🤖</h1>
    <p>Your AI assistant for answers, ideas, images and more.</p>
  </section>

  <div id="chat">

    <div class="message ai">
      👋 Hello! I'm OMplex. Ask me anything.
    </div>

  </div>

  <div class="tools">
    <button onclick="imageMode()">🖼️ Image</button>
    <button onclick="videoMode()">🎬 Video</button>
    <button onclick="clearChat()">🗑️ Clear</button>
  </div>

  <div class="inputBox">

    <input
      id="input"
      type="text"
      placeholder="Ask OMplex anything..."
      autocomplete="off"
    >

    <button onclick="sendMessage()">➤</button>

  </div>

</main>

<script src="app.js"></script>

</body>
</html>
