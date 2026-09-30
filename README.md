<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Sweet Blue ♡</title>

<style>
*{box-sizing:border-box;scroll-behavior:smooth}
body{
 margin:0;font-family:Arial,sans-serif;
 background:#eef9ff;color:#496b82
}
nav{
 background:white;padding:15px;text-align:center;
 position:sticky;top:0;z-index:5;
 box-shadow:0 2px 10px #b9dff2
}
nav b{font:26px Georgia;color:#63afe0;font-style:italic}
nav a{
 color:#57809a;text-decoration:none;margin:0 7px;
 font-size:14px
}
.hero{
 text-align:center;padding:70px 20px;
 background:linear-gradient(#e0f4ff,#fafdff)
}
.hero h1{
 font:italic 55px Georgia;color:#5aa9dc;margin:15px
}
h2,h3{font-family:Georgia;font-style:italic;color:#579dcc}
.hero p{line-height:1.7}
.horario{
 background:white;display:inline-block;
 padding:18px 25px;border-radius:25px;
 box-shadow:0 5px 20px #c5e3f3;
 margin:15px
}
.horario strong{display:block;color:#4b91bf;font-size:20px}
.btn{
 display:inline-block;background:#75bce8;
 color:white;padding:12px 25px;
 border-radius:25px;text-decoration:none
}
section{padding:50px 18px}
.titulo{text-align:center;font-size:30px}
.grid{
 display:grid;
 grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
 gap:18px;max-width:1000px;margin:auto
}
.card{
 background:white;border-radius:20px;overflow:hidden;
 text-align:center;box-shadow:0 5px 18px #cde7f5
}
.card img{width:100%;height:140px;object-fit:cover}
.card div{padding:12px}
.card h3{margin:5px}
.card p{font-size:13px}
.about,.contact{
 background:white;border-radius:30px;
 max-width:800px;margin:auto;
 text-align:center;padding:30px;
 box-shadow:0 5px 20px #cde7f5
}
#horario{text-align:center;background:#dff3ff}
#horario strong{font-size:25px;color:#4d96c4}
footer{
 text-align:center;background:#75bce8;
 color:white;padding:25px
}
</style>
</head>

<body>

<nav>
<b>Sweet Blue ♡</b><br>
<a href="#inicio">Inicio</a>
<a href="#menu">Menú</a>
<a href="#nosotros">Nosotros</a>
<a href="#horario">Horario</a>
<a href="#contacto">Contacto</a>
</nav>

<section class="hero" id="inicio">
<div>♡ ✦ ୨୧ ✦ ♡</div>

<h1>Sweet Blue</h1>

<h2>Un pedacito de dulzura ♡</h2>

<p>
Postres, comidas y bebidas preparadas con mucho cariño
para hacer tus momentos más especiales.
</p>

<div class="horario">
🕐 <i>Horario de atención</i>
<strong>5:00 p. m. — 12:00 a. m.</strong>
</div>

<br>
<a class="btn" href="#menu">Ver menú ✦</a>
</section>


<section id="menu">

<h2 class="titulo">♡ Nuestro menú ♡</h2>

<h2>˚₊‧ Postres ‧₊˚</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1519869325930-281384150729?auto=format&fit=crop&w=500&q=80">
<div><h3>Cupcakes</h3><p>Suaves y deliciosos ♡</p></div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1499636136210-6f4ee915583e?auto=format&fit=crop&w=500&q=80">
<div><h3>Galletas</h3><p>Dulces y crujientes.</p></div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1606313564200-e75d5e30476c?auto=format&fit=crop&w=500&q=80">
<div><h3>Brownies</h3><p>Chocolate en cada bocado.</p></div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1562376552-0d160a2f238d?auto=format&fit=crop&w=500&q=80">
<div><h3>Waffles</h3><p>Dulces y esponjosos.</p></div>
</div>

</div>


<h2>˚₊‧ Comidas ‧₊˚</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?auto=format&fit=crop&w=500&q=80">
<div><h3>Hamburguesas</h3><p>Deliciosas y llenas de sabor.</p></div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1528735602780-2552fd46c7af?auto=format&fit=crop&w=500&q=80">
<div><h3>Sándwiches</h3><p>Una opción rica y práctica.</p></div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1573080496219-bb080dd4f877?auto=format&fit=crop&w=500&q=80">
<div><h3>Papas</h3><p>Perfectas para acompañar.</p></div>
</div>

</div>


<h2>˚₊‧ Bebidas ‧₊˚</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=500&q=80">
<div><h3>Café</h3><p>Calientito y delicioso.</p></div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1544787219-7f47ccb76574?auto=format&fit=crop&w=500&q=80">
<div><h3>Té</h3><p>Suave y reconfortante.</p></div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1572490122747-3968b75cc699?auto=format&fit=crop&w=500&q=80">
<div><h3>Malteadas</h3><p>Cremosas y frías ♡</p></div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1553530666-ba11a7da3888?auto=format&fit=crop&w=500&q=80">
<div><h3>Batidos</h3><p>Refrescantes y deliciosos.</p></div>
</div>

</div>

</section>


<section id="nosotros">
<div class="about">
<h2>♡ Sobre Sweet Blue ♡</h2>
<p>
Sweet Blue es un espacio creado para disfrutar
de comida deliciosa, bebidas refrescantes y
postres llenos de dulzura. ୨୧
</p>
</div>
</section>


<section id="horario">
<h2>♡ Nuestro horario ♡</h2>
<p>🕐 Horario de atención</p>
<strong>5:00 p. m. — 12:00 a. m.</strong>
</section>


<section id="contacto">
<div class="contact">
<h2>♡ Contáctanos ♡</h2>
<p><b>Instagram:</b> @Sweet_Blue</p>
<p><b>Ubicación:</b> Armenia, Quindío</p>
<p><b>Teléfono:</b> +57 123 456 789</p>
<p><b>Horario:</b> 5:00 p. m. — 12:00 a. m.</p>
</div>
</section>


<footer>
♡ ✦ ୨୧ ✦ ♡<br>
Sweet Blue ♡<br>
Un pedacito de dulzura para cada momento.
</footer>

</body>
</html>
