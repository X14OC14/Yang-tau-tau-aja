<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Mafy Remote</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #fdf6f0;
      color: #333;
      line-height: 1.6;
      padding: 2rem;
    }
    h1 {
      color: #ff69b4;
      text-align: center;
    }
    h2 {
      color: #ff1493;
      border-bottom: 2px solid #ffb6c1;
      padding-bottom: 0.3rem;
    }
    code {
      background-color: #fff0f5;
      padding: 0.2rem 0.4rem;
      border-radius: 4px;
      font-weight: bold;
    }
    pre {
      background-color: #ffe4e1;
      padding: 1rem;
      border-radius: 6px;
      overflow-x: auto;
    }
    .note {
      background-color: #fff0f5;
      border-left: 5px solid #ff69b4;
      padding: 0.5rem 1rem;
      margin: 1rem 0;
    }
    .emoji {
      font-size: 1.2rem;
    }
  </style>
</head>
<body>
  <h1>Mafy Remote</h1>
  
  <p class="emoji">🟡 Status: Experimental / Personal Fun Use Only</p>
  
  <h2>Deskripsi</h2>
  <p>
    Repo ini buat <strong>akses jarak jauh aman</strong> via workflow + Tailscale.  
    🔹 Nyalain koneksi remote di runner Windows  
    🔹 Buat user khusus dengan password custom  
    🔹 Tambahkan user ke grup admin & remote access  
    🔹 Instalasi & koneksi <strong>Tailscale</strong> otomatis  
    🔹 Keep-alive supaya akses tetap ready
  </p>
  
  <div class="note">
    ⚠️ Gunakan hanya untuk eksperimen pribadi & belajar. Jangan digunakan untuk hal ilegal 😇
  </div>
  
  <h2>Cara Pakai</h2>
  <ol>
    <li>Fork repo untuk jaga-jaga / eksperimen</li>
    <li>Tambahkan GitHub Secret <code>TAILSCALE_AUTH_KEY</code></li>
    <li>Run workflow dari tab <strong>Actions</strong></li>
    <li>Tunggu log sampai muncul: 
      <pre>
TCP connectivity successful!
Access Info: [IP], Username: Mafy, Password: [custom]
      </pre>
    </li>
    <li>Gunakan client remote favoritmu untuk login via Tailscale IP</li>
  </ol>
  
  <h2>Tips Aman 🛡️</h2>
  <ul>
    <li>Jangan rerun workflow tanpa perlu</li>
    <li>Batasi durasi session (default 1 jam)</li>
    <li>Fork repo sebelum eksperimen supaya repo utama aman</li>
    <li>Password disarankan: 8+ char, simbol, angka, huruf besar & kecil</li>
  </ul>
  
  <h2>Disclaimer ⚠️</h2>
  <p>
    Repo ini untuk <strong>belajar & eksperimen pribadi</strong> saja.  
    Runner bukan server pribadi, jangan abuse.  
    Owner repo tidak bertanggung jawab atas penggunaan yang melanggar TOS.
  </p>

  <p class="emoji">xiaocia</p>
</body>
</html>
