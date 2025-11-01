<!DOCTYPE html>  
<html lang="ja">  
<head>  
  <meta charset="utf-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1">  
  <title>Class Album Access</title>  
  <style>  
    body {  
      font-family: "Segoe UI", sans-serif;  
      text-align: center;  
      background: #fafafa;  
      margin-top: 10%;  
    }  
    input {  
      padding: 10px;  
      font-size: 16px;  
    }  
    button {  
      padding: 10px 20px;  
      font-size: 16px;  
      margin-left: 10px;  
      cursor: pointer;  
    }  
  </style>  
  <script>  
    function checkPassword() {  
      const input = document.getElementById("pw").value.trim();  
      if (input === "pushlimit") {  
        // ✅ Google Drive への正しいURLリンク形式に修正  
        window.location.href = "https://drive.google.com/drive/folders/19GNtlRwKi_CabPJDnr84gwa87rQxzmfP?usp=sharing";  
      } else {  
        alert("パスワードが違います。");  
      }  
    }  
  </script>  
</head>  
<body>  
  <h2>🔒 クラスアルバムへアクセス</h2>  
  <p>合言葉を入力してください</p>  
  <input type="password" id="pw" placeholder="Password">  
  <button onclick="checkPassword()">送信</button>  
</body>  
</html>  
