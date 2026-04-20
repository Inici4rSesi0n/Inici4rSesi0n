<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <style>
    body {
      background-color: #000000;
      background-image: radial-gradient(#0f0f0f 1px, transparent 1px);
      background-size: 40px 40px;
      font-family: 'Courier New', 'Fira Code', monospace;
      color: #0ff;
      padding: 2rem;
      margin: 0;
      text-shadow: 0 0 5px #0ff, 0 0 2px #0f0;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      border: 1px solid #0ff;
      box-shadow: 0 0 20px rgba(0, 255, 255, 0.3), inset 0 0 10px rgba(0, 255, 255, 0.1);
      padding: 2rem;
      background-color: rgba(0, 0, 0, 0.85);
      backdrop-filter: blur(1px);
    }
    h1 {
      font-size: 3rem;
      letter-spacing: -2px;
      color: #ff00cc;
      text-shadow: 3px 3px 0 #00ffff, -2px -2px 0 #ff00cc;
      border-left: 5px solid #0ff;
      padding-left: 20px;
    }
    .glitch {
      animation: glitch 1s infinite;
    }
    @keyframes glitch {
      0% { text-shadow: -2px 0 red, 2px 0 blue; }
      50% { text-shadow: 2px 0 red, -2px 0 blue; }
      100% { text-shadow: -2px 0 red, 2px 0 blue; }
    }
    .subtitle {
      font-size: 1.2rem;
      color: #ffcc00;
      border-bottom: 2px dashed #0ff;
      display: inline-block;
      margin-bottom: 20px;
    }
    .tech {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin: 20px 0;
    }
    .tech span {
      background: #111;
      border: 1px solid #0ff;
      padding: 5px 12px;
      font-family: monospace;
      font-weight: bold;
      color: #0f0;
      box-shadow: 0 0 5px #0ff;
      transition: 0.2s;
    }
    .tech span:hover {
      background: #0ff;
      color: #000;
      box-shadow: 0 0 15px #0ff;
      cursor: default;
    }
    .sigil {
      font-size: 1.8rem;
      letter-spacing: 10px;
      text-align: center;
      margin: 20px 0;
      color: #ff44cc;
      text-shadow: 0 0 8px magenta;
    }
    hr {
      border: none;
      height: 2px;
      background: linear-gradient(90deg, transparent, #0ff, #ff00cc, transparent);
      margin: 25px 0;
    }
    a {
      color: #ff44cc;
      text-decoration: none;
      border-bottom: 1px dotted #0ff;
    }
    a:hover {
      color: #0ff;
      text-shadow: 0 0 8px cyan;
    }
    .lang-section {
      margin-top: 40px;
      padding-top: 20px;
      border-top: 3px double #0ff;
    }
    .y2k-star {
      display: inline-block;
      animation: spin 4s linear infinite;
    }
    @keyframes spin {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }
    footer {
      text-align: center;
      margin-top: 40px;
      font-size: 0.8rem;
      color: #aaa;
    }
  </style>
</head>
<body>
<div class="container">

  <!-- SIGILIO CYBER Y2K -->
  <div class="sigil">
    ⛧ ◉ ⚡ ⌇ 🜍 ⍟ ⓿ ⌇ ⛧
  </div>

  <!-- VERSIÓN INGLÉS -->
  <h1>EDSON <span style="font-size:2rem;">⍟</span></h1>
  <div class="subtitle">✦ Software Engineering Student | Aspiring Cybersecurity Professional (Red & Blue Team) ✦</div>

  <p>⚡ I'm passionate about <strong style="color:#ff44cc;">cybersecurity</strong>, focusing on both defending systems and attacking them <em>ethically</em>. My goal is to specialize in <strong>offensive security</strong> (penetration testing, red teaming) and <strong>defensive strategies</strong> (monitoring, hardening, incident response) to build a complete skill set.</p>

  <div class="sigil" style="font-size:1rem;">﹏﹏﹏ [ TOOLS & ENVIRONMENTS ] ﹏﹏﹏</div>
  <div class="tech">
    <span>Java</span> <span>C</span> <span>Nmap</span> <span>Hydra</span> <span>Wireshark</span> <span>Arch Linux</span> <span>Cisco Packet Tracer</span> <span>HTML5</span> <span>CSS</span>
  </div>

  <div class="sigil" style="font-size:1rem;">⌇ ⌇ ⌇ [ CURRENTLY LEARNING ] ⌇ ⌇ ⌇</div>
  <ul style="list-style-type: none; padding-left: 0;">
    <li>⤞ Network security & ethical hacking</li>
    <li>⤞ Defensive strategies (monitoring, hardening, SIEM)</li>
    <li>⤞ Offensive techniques (penetration testing, red teaming)</li>
    <li>⤞ Secure coding & system hardening</li>
  </ul>

  <div class="sigil" style="font-size:1rem;">✧ FIND ME AROUND THE WEB ✧</div>
  <p style="text-align:center;">
    <a href="#">[GitHub]</a>   |   
    <a href="#">[LinkedIn]</a>   |   
    <a href="#">[Twitter]</a>
  </p>

  <!-- SEPARADOR Y2K -->
  <hr>
