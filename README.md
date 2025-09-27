# Call-me<!doctype html>
<html lang="ur">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>مجھ سے کال کریں</title>
  <style>
    body {
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Noto Sans", "Helvetica Neue", Arial;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
      background: linear-gradient(180deg, #f7fbff, #eaf2ff);
      color: #0b2545;
      text-align: center;
      padding: 24px;
    }
    .card {
      background: white;
      border-radius: 16px;
      box-shadow: 0 8px 30px rgba(20,30,60,0.08);
      padding: 28px;
      max-width: 420px;
      width: 100%;
    }
    h1 { margin: 0 0 8px 0; font-size: 20px; direction: rtl; }
    p { margin: 0 0 18px 0; color: #384a66; direction: rtl; }
    .call-btn {
      display: inline-block;
      text-decoration: none;
      padding: 14px 22px;
      border-radius: 12px;
      font-weight: 600;
      border: none;
      cursor: pointer;
      font-size: 16px;
      background: linear-gradient(180deg, #0b6cff, #0047d6);
      color: white;
    }
    .note { font-size: 13px; color: #6b7688; margin-top: 14px; direction: rtl; }
  </style>
</head>
<body>
  <div class="card" role="main">
    <h1>کال کرنے کے لیے نیچے بٹن دبائیں</h1>
    <p>یہ بٹن دبانے سے آپ کے فون پر ڈائلر کھلے گا اور نمبر خود بخود آ جائے گا۔</p>

    <!-- آپ کا نمبر یہاں لگا دیا گیا ہے -->
    <a class="call-btn" href="tel:+923214185122">ابھی کال کریں</a>

    <p class="note">نوٹ: یہ لنک موبائل پر بہترین کام کرتا ہے۔</p>
  </div>
</body>
</html>
