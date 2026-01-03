# fati-caftan
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>FATI CAFTAN</title>
<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #ffffff;
    color: #333;
}
header {
    background: #f6c1d1;
    padding: 20px;
    text-align: center;
}
header h1 {
    margin: 0;
    color: #8b2c5c;
}
nav {
    margin-top: 10px;
}
nav button {
    margin: 5px;
    padding: 8px 15px;
    border: none;
    background: white;
    color: #8b2c5c;
    cursor: pointer;
    border-radius: 5px;
    font-weight: bold;
}
section {
    padding: 40px;
    text-align: center;
}
section h2 {
    color: #8b2c5c;
}
footer {
    background: #f6c1d1;
    text-align: center;
    padding: 15px;
    color: #8b2c5c;
}
</style>
</head>
<body>

<header>
    <h1>FATI CAFTAN</h1>
    <p id="slogan">أناقة القفطان المغربي</p>
    <nav>
        <button onclick="setLang('ar')">العربية</button>
        <button onclick="setLang('fr')">Français</button>
        <button onclick="setLang('en')">English</button>
    </nav>
</header>

<section>
    <h2 id="title">مرحبا بكم</h2>
    <p id="content">
        FATI CAFTAN تقدم لكم أرقى تصاميم القفطان المغربي بلمسة عصرية وأناقة خالدة.
    </p>
</section>

<footer>
    <p>© 2026 FATI CAFTAN</p>
</footer>

<script>
function setLang(lang) {
    if (lang === 'ar') {
        document.documentElement.lang = "ar";
        document.getElementById("slogan").innerText = "أناقة القفطان المغربي";
        document.getElementById("title").innerText = "مرحبا بكم";
        document.getElementById("content").innerText =
        "FATI CAFTAN تقدم لكم أرقى تصاميم القفطان المغربي بلمسة عصرية وأناقة خالدة.";
    }
    if (lang === 'fr') {
        document.documentElement.lang = "fr";
        document.getElementById("slogan").innerText = "L'élégance du caftan marocain";
        document.getElementById("title").innerText = "Bienvenue";
        document.getElementById("content").innerText =
        "FATI CAFTAN vous propose des créations raffinées du caftan marocain avec une touche moderne.";
    }
    if (lang === 'en') {
        document.documentElement.lang = "en";
        document.getElementById("slogan").innerText = "The elegance of Moroccan caftan";
        document.getElementById("title").innerText = "Welcome";
        document.getElementById("content").innerText =
        "FATI CAFTAN offers elegant Moroccan caftan designs with a modern and timeless style.";
    }
}
</script>

</body>
</html>
