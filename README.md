
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CelTech</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #f5f5f5; }
    header {
      background-color: #1e1e2f;
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1em 2em;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header nav a {
      margin: 0 1em;
      text-decoration: none;
      color: white;
    }
    .seccion {
      padding: 2em;
    }
    .titulo-seccion {
      font-size: 2em;
      margin-bottom: 1em;
    }
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 1.5em;
    }
    .card {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      padding: 1em;
      text-align: center;
    }
    .card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
    }
    .card h3 {
      margin: 1em 0 0.5em;
    }
    .card button {
      background-color: #1e1e2f;
      color: white;
      border: none;
      padding: 0.5em 1em;
      border-radius: 5px;
      cursor: pointer;
    }
    .logo-carrito {
      display: flex;
      align-items: center;
      gap: 2em;
    }
    .carrito-icono {
      width: 24px;
      height: 24px;
      vertical-align: middle;
    }
  </style>
</head>
<body>
  <header>
    <div><strong>CelTech</strong></div>
    <nav>
      <a href="#celulares">Celulares</a>
      <a href="#tablets">Tablets</a>
      <a href="#televisores">Televisores</a>
      <a href="#consolas">Consolas</a>
    </nav>
    <div class="logo-carrito">
      <span><img class="carrito-icono" src="https://cdn-icons-png.flaticon.com/512/263/263142.png" alt="Carrito"> Carrito</span>
    </div>
  </header>

  <div class="seccion" id="celulares">
    <div class="titulo-seccion">Celulares</div>
    <div class="productos">
      <div class="card">
        <img src="data:image/webp;base64,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" alt="Celular">
        <h3>Samsung Galaxy S24 Fe 8 Gb Ram 256 Gb Rom 5g Gris</h3>
        <h4>$2.499.900</h4>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_718466-MLA77263250811_062024-O.webp" alt="Celular">
        <h3>Xiaomi redmi 13 dual sim 256 gb negro 8 gb ram</h3>
 <h4>$800.000</h4>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_887884-MLA74322753760_022024-O.webp" alt="Celular">
        <h3>Samsung Galaxy S24 Ultra 5G Dual SIM 512 GB titanium violet 12 GB RAM</h3>
<h4>$2.900.000</h4>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_728476-MLU78878973712_092024-O.webp" alt="Celular">
        <h3>Apple iPhone 16 Pro Max (256 GB) - Titanio del desierto</h3>
<h4>$5.400.000</h4>
        <button>Agregar al carrito</button>
      </div>
    </div>
  </div>

  <div class="seccion" id="tablets">
    <div class="titulo-seccion">Tablets</div>
    <div class="productos">
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_911212-MLU72627488378_112023-O.webp" alt="Tablet">
        <h3>Tablet Lenovo Tab M9 4gb 64gb 4g Lte 9 Azul</h3>
<h4>$600.000</h4>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_949487-MLA79796140102_102024-O.webp" alt="Tablet">
        <h3>Galaxy Tab S6 Lite 2024 4gb 128gb Gray Color Gris</h3>
<h4>$1.400.000</h4>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_927528-MLU77335548226_072024-O.webp" alt="Tablet">
        <h3>Tableta con pantalla Xiaomi Redmi Pad Se 11 de 256 GB y 8 GB de RAM, color verde</h3>
<h4>$800.000</h4>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_891613-MLA52988782504_122022-O.webp" alt="Tablet">
        <h3>iPad 10ª Generación A2696 10.9" 64GB rosa 4GB de memoria RAM</h3>
<h4>$1.300.000</h4>
        <button>Agregar al carrito</button>
      </div>
    </div>
  </div>

  <div class="seccion" id="televisores">
    <div class="titulo-seccion">Televisores</div>
    <div class="productos">
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_613346-MLU75858730250_042024-O.webp" alt="Televisor">
        <h3>Televisor Smart 50 Crystal Du8200</h3>
<h4>$1.800.000</h4>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_798711-MLU79285460287_092024-O.webp" alt="Televisor">
        <h3>Televisor Kalley 40 Pulgadas K-rtv40hd Smart Tv Roku Tv</h3>
<h4>$700.000</h4>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_788217-MLA79416615238_092024-O.webp" alt="Televisor">
        <h3>Smart TV Hyundai HYLED5017W4KM 50'' 4K LED</h3>
<h4>$1.400.000</h4>
        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_839067-MLU77307020403_062024-O.webp" alt="Televisor">
        <h3>Televisor Samsung Smart 48 Oled S90d</h3>
<h4>$2.700.000</h4>
        <button>Agregar al carrito</button>
      </div>
    </div>
  </div>

  <div class="seccion" id="consolas">
    <div class="titulo-seccion">Consolas</div>
    <div class="productos">
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_907331-MLA82916301654_032025-O.webp" alt="Consola">
        <h3>Consola Nintendo Switch Oled Mario Wonder + 12 Meses Online</h3>
<h4>$1.600.000</h4>

        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_970771-MLA73347645092_122023-O.webp" alt="Consola">
        <h3>Consola Sony PlayStation 5 Slim Blanco 4K 1TB Digital</h3>
<h4>$2.150.000</h4>

        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_872052-MLU78686375727_082024-O.webp" alt="Consola">
        <h3>Microsoft Xbox Series S 115505203817 1TB Standard color negro 2023</h3>
<h4>$2.500.000</h4>

        <button>Agregar al carrito</button>
      </div>
      <div class="card">
        <img src="https://http2.mlstatic.com/D_NQ_NP_692966-MLU73202686767_122023-O.webp" alt="Consola">
        <h3>Consola Valve Steam Deck 512GB Standard color negro</h3>
<h4>$3.400.000</h4>

        <button>Agregar al carrito</button>
      </div>
    </div>
  </div>

</body>
</html>
