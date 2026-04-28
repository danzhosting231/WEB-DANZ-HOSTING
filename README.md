#WEB DANZ HOSTING OWN
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DANZZ HOSTING OWN</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: black;
    color: white;
    text-align: center;
    overflow: hidden;
}

/* ANIMASI BACKGROUND */
body::before {
    content: "";
    position: fixed;
    width: 200%;
    height: 200%;
    background: radial-gradient(circle, red, black);
    animation: bgMove 10s linear infinite;
    z-index: -1;
}

@keyframes bgMove {
    0% { transform: translate(0,0); }
    50% { transform: translate(-25%, -25%); }
    100% { transform: translate(0,0); }
}

.container {
    padding: 50px;
    animation: fadeIn 2s ease;
}

/* FADE MASUK */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
}

h1 {
    font-size: 42px;
    color: red;
    animation: glow 1.5s infinite alternate;
}

/* GLOW TEXT */
@keyframes glow {
    from { text-shadow: 0 0 10px red; }
    to { text-shadow: 0 0 30px red, 0 0 50px red; }
}

.card {
    background: rgba(0,0,0,0.7);
    border: 1px solid red;
    border-radius: 15px;
    padding: 20px;
    margin: 20px auto;
    width: 90%;
    max-width: 400px;
    box-shadow: 0 0 25px red;
    animation: fadeIn 2s ease;
}

a {
    color: cyan;
    text-decoration: none;
}

/* BUTTON ANIMASI */
.btn {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 25px;
    background: red;
    color: white;
    border-radius: 10px;
    text-decoration: none;
    box-shadow: 0 0 15px red;
    transition: 0.3s;
}

.btn:hover {
    transform: scale(1.1);
    background: darkred;
}

/* TEXT BERKEDIP */
.blink {
    animation: blink 1s infinite;
}

@keyframes blink {
    50% { opacity: 0.5; }
}
</style>
</head>

<body>

<div class="container">
    <h1>DANZZ HOSTING OWN</h1>

    <div class="card">
        <p><b>Nomor Admin:</b></p>
        <p class="blink">082319667803</p>

        <p><b>TikTok:</b></p>
        <a href="https://tiktok.com/@all.projek6" target="_blank">
            tiktok.com/@all.projek6
        </a>

        <p style="margin-top:20px;">
            Yang mau buy langsung PM WA aja 🔥
        </p>

        <a class="btn" href="https://wa.me/6282319667803" target="_blank">
            CHAT WHATSAPP
        </a>
    </div>
</div>

</body>
</html>
