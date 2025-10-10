
[index.html](https://github.com/user-attachments/files/22840375/index.html)
<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Domů</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<nav class="custom-nav">
  <div class="container">
    <a href="index.html">Domů</a>
    <a href="pokus.html">Pokus 1</a>
    <a href="pokus2.html">Pokus 2</a>
    <a href="pokus3.html">Bootstrap stránka</a>
  </div>
</nav>

<div class="container">
  <h1 style="color:#0d6efd;">Úvodní stránka (ruční CSS + inline styl)</h1>
  <div class="card">
    <p>Tady začíná náš malý web. Všechny stránky mají stejné menu a jsou mezi sebou prolinkované.</p>
  </div>
</div>

<footer class="container">© 2025 – školní ukázka</footer>
</body>
</html>


[pokus.html](https://github.com/user-attachments/files/22840376/pokus.html)<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pokus 1 (ruční styl)</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<nav class="custom-nav">
  <div class="container">
    <a href="index.html">Domů</a>
    <a href="pokus.html">Pokus 1</a>
    <a href="pokus2.html">Pokus 2</a>
    <a href="pokus3.html">Bootstrap stránka</a>
  </div>
</nav>

<div class="container">
  <h1>Pokus 1 – ruční CSS</h1>
  <div class="card">
    <p style="font-style: italic;">Toto je příklad s inline stylem (kurzíva).</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cumque, quam?</p>
  </div>
</div>

<footer class="container">Navigace je stejná na všech stránkách.</footer>
</body>
</html>

[pokus2.html](https://github.com/user-attachments/files/22840377/pokus2.html)<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pokus 2 (ruční styl)</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<nav class="custom-nav">
  <div class="container">
    <a href="index.html">Domů</a>
    <a href="pokus.html">Pokus 1</a>
    <a href="pokus2.html">Pokus 2</a>
    <a href="pokus3.html">Bootstrap stránka</a>
  </div>
</nav>

<div class="container">
  <h1>Pokus 2 – ruční CSS</h1>
  <div class="card">
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro ex est tenetur eum!
    Laudantium illum, consequuntur fugiat ullam accusantium laboriosam praesentium necessitatibus fuga non,
    blanditiis, vel nam beatae modi doloribus.</p>
  </div>
</div>

<footer class="container">Stejné menu na všech stránkách – zadaný požadavek splněn.</footer>
</body>
</html>


[pokus3.html](https://github.com/user-attachments/files/22840380/pokus3.html)<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pokus 3 (Bootstrap)</title>
  <!-- Bootstrap 5.3.3 CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- STEJNÉ MENU – varianta s Bootstrapem -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container">
    <a class="navbar-brand" href="index.html">Moje stránka</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Přepnout navigaci">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="index.html">Domů</a></li>
        <li class="nav-item"><a class="nav-link" href="pokus.html">Pokus 1</a></li>
        <li class="nav-item"><a class="nav-link" href="pokus2.html">Pokus 2</a></li>
        <li class="nav-item"><a class="nav-link active" aria-current="page" href="pokus3.html">Bootstrap stránka</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="container mt-4">
  <h1>Bootstrap stránka</h1>
  <p>Tato stránka používá Bootstrap 5.3 s <strong>responzivním</strong> menu. Zmenši okno a uvidíš sbalené menu.</p>

  <div class="row g-3">
    <div class="col-md-4">
      <div class="card">
        <div class="card-body">
          <h5 class="card-title">Karta 1</h5>
          <p class="card-text">Ukázka Bootstrap komponent (karta).</p>
          <a class="btn btn-primary" href="index.html">Domů</a>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card">
        <div class="card-body">
          <h5 class="card-title">Karta 2</h5>
          <p class="card-text">Další obsah k demonstraci gridu.</p>
          <a class="btn btn-outline-primary" href="pokus.html">Pokus 1</a>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card">
        <div class="card-body">
          <h5 class="card-title">Karta 3</h5>
          <p class="card-text">Stejné položky menu jako na ostatních stránkách.</p>
          <a class="btn btn-outline-secondary" href="pokus2.html">Pokus 2</a>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Bootstrap Bundle JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

[README.txt](https://github.com/user-attachments/files/22840383/README.txt)NÁVOD K ODEVZDÁNÍ
==================
Cíl:
- Několik prolinkovaných statických HTML souborů.
- Dvě stránky s ručními styly ze souboru style.css + vyzkoušet inline styl.
- Ve třetím souboru zapnout Bootstrap 5.3 a vložit základní responzivní menu.
- Menu zkopírovat do všech HTML tak, aby bylo stejné (při navigaci se neměnilo).





[style.css](https://github.com/user-attachments/files/22840385/style.css)
/* style.css – ruční styly pro dvě stránky */
* { box-sizing: border-box; }
body {
  font-family: Arial, Helvetica, sans-serif;
  background: #f7f7f7;
  margin: 0;
  color: #222;
}
.container { max-width: 980px; margin: 0 auto; padding: 16px; }
.custom-nav { background: #333; }
.custom-nav .container { display: flex; gap: 16px; align-items: center; padding: 10px 0; }
.custom-nav a { color: #fff; text-decoration: none; padding: 8px 10px; border-radius: 6px; }
.custom-nav a:hover { background: rgba(255,255,255,0.15); }
.card { background: #fff; border-radius: 10px; padding: 16px; box-shadow: 0 6px 18px rgba(0,0,0,.06); margin-top: 16px; }
footer { margin: 40px 0 20px; color: #666; font-size: .95rem; }



