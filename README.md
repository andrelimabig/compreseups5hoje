<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PlayStation 5 – Apresentação Animada</title>

    <style>
        /* -------------------- GLOBAL -------------------- */
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #0d0d0d;
            color: white;
            overflow-x: hidden;
            animation: fadeInPage 1.3s ease-in forwards;
        }

        @keyframes fadeInPage {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* -------------------- HEADER -------------------- */
        header {
            background: linear-gradient(90deg, #003087, #0a0a0a);
            padding: 60px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        header h1 {
            font-size: 52px;
            margin: 0;
            animation: slideDown 1.2s ease-out;
        }

        header p {
            font-size: 18px;
            opacity: 0;
            animation: fadeInUp 1.5s ease-out forwards;
            animation-delay: 0.5s;
        }

        /* brilho animado no topo */
        header::after {
            content: "";
            position: absolute;
            top: 0;
            left: -100%;
            width: 50%;
            height: 100%;
            background: linear-gradient(120deg, transparent, rgba(255,255,255,0.3), transparent);
            animation: shine 5s infinite;
        }

        @keyframes shine {
            0% { left: -100%; }
            50% { left: 150%; }
            100% { left: 150%; }
        }

        /* -------------------- SEÇÕES -------------------- */
        .section {
            padding: 60px 10%;
            animation: fadeIn 1.2s ease-out forwards;
            opacity: 0;
        }

        .section:nth-child(odd) {
            animation-delay: 0.3s;
        }

        .section:nth-child(even) {
            animation-delay: 0.6s;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(40px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* -------------------- IMAGEM -------------------- */
        .ps5-image {
            width: 100%;
            max-width: 500px;
            display: block;
            margin: 20px auto;
            filter: drop-shadow(0 0 20px #003087);
            animation: float 3s ease-in-out infinite;
        }

        /* efeito flutuante */
        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0); }
        }

        /* -------------------- FEATURES -------------------- */
        .features {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 30px;
        }

        .feature-box {
            background: #1c1c1c;
            padding: 20px;
            border-radius: 10px;
            flex: 1 1 260px;
            border: 1px solid #333;
            transform: scale(1);
            transition: transform 0.3s, box-shadow 0.3s;
            animation: fadeInUp 1.2s ease-out forwards;
            opacity: 0;
        }

        .feature-box:nth-child(1) { animation-delay: 0.4s; }
        .feature-box:nth-child(2) { animation-delay: 0.6s; }
        .feature-box:nth-child(3) { animation-delay: 0.8s; }
        .feature-box:nth-child(4) { animation-delay: 1s; }

        /* animação de entrada */
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(40px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* efeito hover */
        .feature-box:hover {
            transform: scale(1.07);
            box-shadow: 0 0 25px #0072ce;
        }

        /* -------------------- FOOTER -------------------- */
        footer {
            text-align: center;
            padding: 30px;
            background: #0a0a0a;
            margin-top: 40px;
            animation: fadeIn 1.5s ease-out;
        }

    </style>
</head>
<body>

<header>
    <h1><img src="logops5.png" alt="logo"></h1> <div class="image-container">
  

<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Título Brilhante</title>

<style>
    body {
        background: #000;
        text-align: center;
        padding-top: 80px;
        font-family: Arial, sans-serif;
    }

    .glow {
        font-size: 60px;
        color: #fff;
        text-shadow: 
            0 0 5px #00aaff,
            0 0 10px #00aaff,
            0 0 20px #00aaff,
            0 0 40px #0088dd,
            0 0 80px #0088dd;
        transition: 0.3s;
        cursor: pointer;
    }

    .glow:hover {
        text-shadow:
            0 0 10px #00ccff,
            0 0 20px #00ccff,
            0 0 40px #00ccff,
            0 0 80px #00ccff,
            0 0 120px #00ccff,
            0 0 160px #00ccff;
        color: #cceeff;
    }
</style>

</head>
<body>

<h1 class="glow">Compre seu Playstation 5 agora!!!</h1>

</body>
</html>

    
</header>

<section class="section">
 
    <img class="ps5-image" 
        <img src="ab.png" alt="logo" width="150"
         
    
       <p><h1 class="glow">Compra Totalmente segura direto pelo Mercado Livre</h1> </p>
    
</section>

<section class="section">
    
    <style>
.brilho-amarelo {
    font-size: 26px;
    color: #fff8a0;
    text-shadow:
        0 0 5px #ffe066,
        0 0 8px #ffd53a,
        0 0 14px #ffcc00,
        0 0 23px #ffb700;
    transition: 0.2s;
}

.brilho-amarelo:hover {
    text-shadow:
        0 0 8px #fff7a8,
        0 0 14px #ffea7a,
        0 0 26px #ffd000,
        0 0 45px #ffbd00,
        0 0 65px #ffb700;
}
</style>

<h3 class="brilho-amarelo">Produtos Principais</h3>
    </section>
<body>
<div>
<style>
/* Estilo aplicado apenas aos botões com classe .btn-img */
.btn-img-container {
    display: flex;
    gap: 10px; /* espaço entre os botões */
}

.btn-img-container a img.btn-img {
    width: 120px;   /* ajuste o tamanho aqui */
    height: 120px;  /* deixa todas iguais */
    object-fit: cover; /* ajusta a imagem dentro do botão */
    border-radius: 10px; /* opcional */
    cursor: pointer;
}
</style>

<style>
.box {
    position: relative;
    display: inline-block;
}

.center-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    font-size: 24px;
    font-weight: bold;
    text-shadow: 0 0 8px black;
}
</style>

<style>
.box {
    position: relative;
    display: inline-block;
}

.margin-top {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    font-size: 24px;
    font-weight: bold;
    text-shadow: 0 0 8px black;
}
</style>


    <section class="section">
        <div class="features">
        <div class="btn-img">
     <div class="btn-img-container">
            
      <div class="feature-box" btn-img btn-img-container>
<a href="https://mercadolivre.com/sec/1pJyU3T" target="_blank"rel="noopener noreferrer">
    <img src="5ps5.png" alt="Botão 3" style="width:300px; height: 110px;"><div class="center-text">PS5 R$2.999</div>
</a></div>      
            

<div class="feature-box" btn-img btn-img-container>
   <a  href="https://mercadolivre.com/sec/2N9Ppz8"target="_blank" rel="noopener noreferrer">
       <img src="psp5555.png" alt="Botão 2" style="width:300px; height: 110px;"><div class="center-text">PS5Pro R$5.999</div>
</a> </div>



<div class="feature-box" btn-img btn-img-container>
<a href="https://mercadolivre.com/sec/28Ji7Zz"target="_blank" rel="noopener noreferrer">
       <img src="vrps5.png"alt="Botão 1" style="width:300px; height: 110px;"><div class="center-text">VR PS5 R$3.338</div>
    </div>
    </a> </div>
 

</div>
    </body>



</section>


<section class="section">
    <h3 class="brilho-amarelo">Frete Grátis</h3>
    <p>
     </section> 
 
      <img src="logotps.png" alt="Logo" style="width:auto; height:auto;">

<footer>
  <h1 class="glow">Parcelamento em até 18x (sem juros)</h1>
</footer>

</body>

      

       

 

