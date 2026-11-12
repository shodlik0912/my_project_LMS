
<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>my_project_LMS | Shodlikbek</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background: linear-gradient(135deg, #10172e, #182c50);
    color: white;
    min-height: 100vh;
}

header {
    padding: 25px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #101a33;
    box-shadow: 0 5px 20px #0005;
}

.logo {
    font-size: 27px;
    font-weight: bold;
    color: #38bdf8;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 25px;
}

nav a:hover {
    color: #38bdf8;
}

.hero {
    text-align: center;
    padding: 100px 20px;
}

.hero h1 {
    font-size: 48px;
    margin-bottom: 20px;
}

.hero h1 span {
    color: #38bdf8;
}

.hero p {
    color: #cbd5e1;
    font-size: 18px;
    margin-bottom: 30px;
}

button {
    padding: 14px 30px;
    border: none;
    border-radius: 30px;
    background: #38bdf8;
    color: #102039;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
}

button:hover {
    background: white;
    transform: scale(1.05);
}

.cards {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 25px;
    padding: 20px;
}

.card {
    background: #1e3155;
    width: 260px;
    padding: 30px;
    border-radius: 18px;
    text-align: center;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
    background: #25436e;
}

.card h2 {
    color: #38bdf8;
    margin-bottom: 15px;
}

.card p {
    color: #cbd5e1;
}

footer {
    text-align: center;
    padding: 30px;
    margin-top: 50px;
    background: #101a33;
    color: #94a3b8;
}

</style>
</head>

<body>

<header>
    <div class="logo">MY_PROJECT_LMS</div>
    <nav>
        <a href="#">Bosh sahifa</a>
        <a href="#courses">Kurslar</a>
        <a href="#about">Biz haqimizda</a>
    </nav>
</header>

<section class="hero">
    <h1>Welcome to <span>My LMS</span></h1>
    <p>Bilim olish — kelajak sari eng katta qadam!</p>
    <button onclick="start()">Boshlash</button>
</section>

<section class="cards" id="courses">

    <div class="card">
        <h2>💻 Dasturlash</h2>
        <p>HTML, CSS, JavaScript va Python tillarini o‘rganing.</p>
    </div>

    <div class="card">
        <h2>📚 Ta'lim</h2>
        <p>O‘zingiz uchun yangi bilim va ko‘nikmalarni egallang.</p>
    </div>

    <div class="card">
        <h2>🏆 Natijalar</h2>
        <p>O‘z bilimlaringizni rivojlantiring va yutuqlarga erishing.</p>
    </div>

</section>

<footer id="about">
    <h3>Shodlikbek</h3>
    <p>Username: web_wuzer_oo1</p>
    <p>© 2026 MY_PROJECT_LMS | Barcha huquqlar himoyalangan</p>
</footer>

<script>
function start() {
    alert("Xush kelibsiz, Shodlikbek! LMS platformasiga marhamat!");
}
</script>

</body>
</html>

