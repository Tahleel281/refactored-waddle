<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Submit Your Info</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, sans-serif;
      background: linear-gradient(to bottom, #ffffff, #ffc0cb); /* 🔹 White & Pink gradient */
      min-height: 100vh;
      display: grid;
      place-items: center;
      color: #333;
      padding: 24px;
    }
    .form-container {
      width: 400px;
      background: #ffffff; /* 🔹 Form white */
      border: 1px solid #ffc0cb;
      border-radius: 20px;
      padding: 28px;
      box-shadow: 0 12px 32px rgba(0,0,0,0.2);
    }
    h2 { 
      margin: 0 0 16px; 
      text-align: center; 
      color: #d63384; /* 🔹 Heading in pink shade */
    }
    .form-group { margin: 14px 0; text-align: left; }
    label { 
      display:block; 
      margin-bottom:6px; 
      color:#d63384; /* 🔹 Labels pink */
      font-weight:700; 
      font-size:15px;
    }
    input {
      width: calc(100% - 20px);
      padding:12px 14px; 
      border-radius:14px;
      border:1px solid #ffc0cb; /* 🔹 Pink outline */
      background: #fff; 
      color:#333; 
      outline:none; 
      transition:.2s;
      font-size:14px;
      display: block;
      margin: 0 auto;
    }
    input:focus {
      border-color:#d63384; 
      box-shadow:0 0 8px rgba(214,51,132,0.5);
    }
    button {
      margin-top:18px; 
      width: calc(100% - 20px);
      padding:13px; 
      border:0; 
      border-radius:14px;
      background: #d63384; /* 🔹 Solid pink, no gradient */
      color:#fff;
      font-weight:700; 
      letter-spacing:.3px; 
      cursor:pointer; 
      transition:.2s;
      font-size:15px;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }
    button:hover { box-shadow:0 12px 26px rgba(255,192,203,.6); } /* 🔹 Soft pink glow */
    .note { margin-top:12px; font-size:12px; text-align:center; opacity:.8; color:#666; }
  </style>
</head>
<body>
  <div class="form-container">
    <h2>Submit Your Info</h2>
    <form action="https://hook.eu2.make.com/7ubn8ca7mosgsqvjxzcjh7twhh2r7ru9" method="POST" autocomplete="off">
      
      <div class="form-group">
        <label for="name">Name</label>
        <input id="name" name="name" type="text" placeholder="Enter your name" required>
      </div>

      <div class="form-group">
        <label for="email">Email</label>
        <input id="email" name="email" type="email" placeholder="Enter your email" required>
      </div>

      <div class="form-group">
        <label for="company">Company</label>
        <input id="company" name="company" type="text" placeholder="Enter your company name">
      </div>

      <div class="form-group">
        <label for="budget">Budget</label>
        <input id="budget" name="budget" type="text" placeholder="Enter your budget">
      </div>

      <div class="form-group">
        <label for="interested_service">Interested Service</label>
        <input id="interested_service" name="interested_service" type="text" placeholder="Enter service you’re interested in">
      </div>

      <button type="submit">Submit</button>
      <div class="note">Powered by Make Webhook</div>
    </form>
  </div>
</body>
</html>
