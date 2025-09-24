<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Temporizador SCG</title>
  <style>
    :root {
      --blue: #007BFF;
      --blue-light: #66b2ff;
      --bg-gradient: linear-gradient(135deg, #89f7fe, #66a6ff);
      --white: #fff;
      --dark: #333;
      --muted: #aaa;
    }
    body {
      margin: 0;
      font-family: "Segoe UI", Roboto, Arial, sans-serif;
      background: var(--bg-gradient);
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    .topbar {
      background: rgba(255,255,255,0.1);
      backdrop-filter: blur(8px);
      padding: 25px 20px;
      text-align: center;
      border-bottom-left-radius: 30px;
      border-bottom-right-radius: 30px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
    .topbar h1 {
      font-size: 36px;
      font-weight: 900;
      margin: 0;
      color: white;
    }
    .topbar p {
      margin: 5px 0 0;
      font-size: 16px;
      color: var(--white);
      opacity: 0.8;
    }
    .container {
      flex: 1;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      padding: 20px;
    }
    .inputs {
      display: flex;
      gap: 15px;
      margin: 20px 0;
      flex-wrap: wrap;
      justify-content: center;
    }
    .inputs input, .inputs select {
      padding: 10px;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 16px;
      min-width: 180px;
    }
    .timer {
      font-size: 60px;
      font-weight: bold;
      margin: 
