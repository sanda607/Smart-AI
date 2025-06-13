<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SmartAI | AI Website</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>SmartAI</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Features</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to SmartAI</h2>
    <p>Experience the future of artificial intelligence in your browser.</p>
    <button onclick="startDemo()">Try Demo</button>
  </section>

  <section class="demo">
    <h3>Chat with SmartAI</h3>
    <div class="chat-box" id="chat-box">
      <p><strong>You:</strong> Hello</p>
      <p><strong>AI:</strong> Hi there! How can I help you today?</p>
    </div>
    <input type="text" id="user-input" placeholder="Ask something..." />
    <button onclick="sendMessage()">Send</button>
  </section>

  <footer>
    <p>© 2025 SmartAI. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
