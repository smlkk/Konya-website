# Konya-website MELEK_96
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Konya Şehri</title>
    <style>
     body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color: orange;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}

.info-box {
    background-color:white;
    color: #333;
    padding: 20px;
    margin: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

    </style>
    <script>
        function keşfSayfasınaGit(page) {
            window.location.href = page + ".html";
        }
    </script>
</head>
<body>
    <header>
        <h1>Konya Şehri</h1>
        <p>Hoş Geldiniz! Konya'yı Keşfedin.</p>
        <button onclick="keşfSayfasınaGit('kesf')">Konya'yı Keşfedin</button>
        <button onclick="keşfSayfasınaGit('ulasim')">Ulaşım</button>
        <button onclick="keşfSayfasınaGit('yemekler')">Yemekler</button>
        <button onclick="keşfSayfasınaGit('iletisim')">İletişim</button>
    </header>

    <section id="about" class="info-box">
        <h2>Konya Hakkında</h2>
        <p>Konya, Türkiye'nin iç bölgelerinden biridir ve tarihi zenginliği ile ön plana çıkar. Türkiye'nin en büyük yüzölçümüne sahip şehirlerinden biridir.</p>
        <p>Şehir, tarihi boyunca pek çok medeniyete ev sahipliği yapmıştır. Özellikle Selçuklu İmparatorluğu'nun başkenti olarak önemli bir rol oynamıştır.</p>
        <p>Konya, Mevlana Celaleddin Rumi'nin türbesine ev sahipliği yapmasıyla da bilinir. Mevlana, dünyanın en önemli mistik şairlerinden biridir.</p>
        <p>İslam kültüründe önemli bir yere sahip olan Konya, camileri, medreseleri ve tarihi yapıları ile kültürel bir mirasa sahiptir.</p>
        <p>Şehir aynı zamanda tarım ve hayvancılık faaliyetleriyle de dikkat çeker. Özellikle buğday tarımı yaygındır.</p>
    </section>

    <!-- Diğer bilgi kutuları ve içerikleri buraya eklenebilir -->

    <footer>
        <p>&copy; 2023 Konya Şehri</p>
    </footer>
</body>
</html>
