- 👋 Hi, I’m @getulio
- 👀 I’m interested in Programation 
- 🌱 I’m currently learning Javascript
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me: Email:getcontamach@gmail.com
  or  https://www.linkedin.com/in/get%C3%BAlio-machado-a08076202?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BwGVyU1ArRaa7LyM98bzHzQ%3D%3D

<!---
getuli/getuli is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
.Projeto de crição de grade de produtos de uma loja:
HTML:
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>grid de produtos</title>
  <link rel="stylesheet" href="site.css">
</head>

<body>
  <!-- cabeçalho -->
  <header class="cabeca">
    <h1>Segue os produtos da loja:</h1>
  </header>

  <!-- corpo central -->
  <main>
    <section class="containerpai">
      <div class="container">
        <div class="foto" id="image">
          <img src="transferir.jpeg" alt="produto">
          <br>
          <h3>Produto 1</h3>
          <p>Não perca tempo, qualidade sem precedente</p>
          <p>por apenas 89,99</p>
          <br>
          <br>
          <a class="btn" href="#">Comprar</a>
        </div>
      </div>

      <div class="container">
        <div class="foto" id="image">
          <img src="images (1).jpeg" alt="produto">
          <h3>Produto 2</h3>
          <p>Não perca tempo, qualidade sem precedente</p>
          <p>por apenas 89,99</p>
          <br>
          <br>
          <a class="btn" href="#">Comprar</a>
        </div>
      </div>

      <div class="container">
        <div class="foto" id="image">
          <img src="images (2).jpeg" alt="produto">
          <h3>Produto 3</h3>
          <p>Não perca tempo, qualidade sem precedentes</p>
          <p>por apenas 89,99</p>
          <br>
          <br>
          <a class="btn" href="#">Comprar</a>
        </div>
      </div>

      <div class="container">
        <div class="foto" id="image">
          <img src="images (3).jpeg" alt="produto">
          <h3>Produto 4</h3>
          <p>Não perca tempo, qualidade sem precedente</p>
          <p>por apenas 89,99</p>
          <br>
          <br>
          <a class="btn" href="#">Comprar</a>
        </div>
      </div>

      <div class="container">
        
          <img src="images (4).jpeg" alt="produto">
          <h3>Produto 5</h3>
          <p>Não perca tempo, qualidade sem precedente</p>
          <p>por apenas 89,99</p>
          <br>
          <br>
          <a class="btn" href="#">Comprar</a>
        </div>
      </div>

      <div class="container">
        <div class="foto" id="image">
          <img src="transferir (3).jpeg" alt="produto">
          <h3>Produto 6</h3>
          <p>Não perca tempo, qualidade sem precedente</p>
          <p>por apenas 89,99</p>
          <br>
          <br>
          <a class="btn" href="#">Comprar</a>
          
        </div>
      </div>
    </section>
  </main>

  <!-- rodapé -->
  <footer class="rodape">
    <p>direitos autorais reservados, &copy; 2023</p>
  </footer>
</body>

</html>


CSS:*{
    padding: 0px;
    margin: 0px;
    box-sizing: border-box;
    font-family: Helvetica,;
}
h1{
    background-color: #000;
    color: #fff;
    padding: 40px;
    text-align: center;
    border-bottom:solid salmon;
}

.containerpai{
    background-color: #EEE;
    min-height: 60vh;
    padding: 50px;
}
.container{
    height: 300px;
    width: 100%%;
    display: inline-block;
    margin-bottom: 10px;
    back-groundposition: center;}

.btn{
    background-color: rgb(13, 14, 13);
    padding: 15px;
    margin: 20px;
    text-align: center;
    color: #EEE;
    text-decoration: none;
    border-bottom: 5px purple;
}
.btn:hover{background-color: blue;}
.rodape{
    color:rgb(25,36,153);
background-color:rgb(243, 243, 45);
padding: 40px;
text-align: center;
border-top: 3px blue;
font-size: 29px;}

