<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <link rel="stylesheet" href="style.css">
   <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
</head>
<body>

  <header>
    <h1>Feliz Dia dos Namorados ❤️</h1>
    <p>Para minha digníssima ❤️</p>
  </header>

  <section>
    <h2>Nossas lembranças:</h2>
  <div class="photos">
    <figure>
      <img class="fade-in" src="image.png" alt="Foto 1" />
      <figcaption>fazendo aquele treino monstro</figcaption>
    </figure>
    <figure>
      <img class="fade-in" src="cinema.png" alt="Foto 2" />
      <figcaption>No cinema juntos</figcaption>
    </figure>
    <figure>
      <img class="fade-in" src="praia.png" alt="Foto 3" />
      <figcaption>Na praia juntos</figcaption>
    </figure>
  </div>

    <div class="text-content">
      <h2>Para você...</h2>
      <p>Meu amor,</p>

<p>Desde que você entrou na minha vida, tudo ficou mais bonito. Cada sorriso seu é um presente, e cada momento com você é especial.</p>

<p>Eu sou imensamente grato por ter você na minha vida. Você é uma das maiores bênçãos que Deus me deu, e tudo o que eu mais quero é te ver feliz, com esse sorriso lindo e único que ilumina até os meus dias mais difíceis. Você é especial demais, e eu admiro cada detalhe seu. Sou seu fã número 1, de coração.</p>

<p>Quero te fazer se sentir amada, segura e valorizada todos os dias. Não quero que o que eu sinto fique só nas palavras — quero te provar com atitudes, com cuidado, com presença. Pode sempre contar comigo. Eu quero ser o teu porto seguro, o teu refúgio, o teu lar.</p>

<p>Você é incrível, perfeita do jeitinho que é. E eu, sinceramente, fico bobo com o teu sorriso, com o teu jeito, com essa beleza tão única que só você tem. Às vezes eu nem sei como expressar tudo o que sinto, mas preciso que você saiba: você é a única que eu quero. A pessoa com quem eu sonho dividir minha vida, construir um futuro, enfrentar os desafios e celebrar todas as conquistas.</p>

<p>Não existe mais ninguém pra mim. É você.<br/>
O meu coração é seu. E toda vez que te vejo, é como se fosse a primeira vez — ele dispara, meus olhos brilham, e eu só consigo pensar que você é a resposta de todas as minhas orações.</p>

<p>Se tiver algo que eu possa te fazer entender, é isso:<br/>
Você é tudo pra mim.<br/>
É com você que eu quero viver, crescer, sonhar, amar e caminhar todos os dias da minha vida.</p>

<p>Que você tenha um dia maravilhoso.<br/>
Fica com Deus.<br/>
Eu estarei aqui, sempre, pra tudo o que você precisar.<br/>
Eu te amo profundamente, e vou te amar como Cristo ama a Sua igreja.</p>

<p>Minha princesa, minha futura esposa, meu amor pra vida inteira.🤍✨</p>

    </div>

    <div class="bible-verses">
  <h2>Versículo💖</h2>
  <p>
    📖 <strong>1 Coríntios 13:4-7</strong><br/>
    O amor é paciente, o amor é bondoso. Não inveja, não se vangloria, não se orgulha. 
    Não maltrata, não procura seus interesses, não se ira facilmente, não guarda rancor. 
    O amor não se alegra com a injustiça, mas se alegra com a verdade. Tudo sofre, tudo crê, tudo espera, tudo suporta.
  </p>

    <div class="languages">
     
        <h2>Eu te amo em várias línguas 🌍</h2>
      <p>
        Português: Eu te amo<br/>
        Inglês: I love you<br/>
        Espanhol: Te amo<br/>
        Francês: Je t'aime<br/>
        Italiano: Ti amo<br/>
        Alemão: Ich liebe dich<br/>
        Japonês: 愛してる (Aishiteru)<br/>
        Coreano: 사랑해요 (Saranghaeyo)<br/>
        Chinês: 我爱你 (Wǒ ài nǐ)<br/>
        Árabe: أحبك (Uḥibbuka/Uḥibbuki)<br/>
        Russo: Я тебя люблю (Ya tebya lyublyu)
      </p>
    </div>
  </div>
  </section>

  <footer>
    <b>Feito para você — Feliz dia dos Namorados, minha princesa!!</b>
  </footer>
<script>
    function createHeart() {
      const heart = document.createElement("div");
      heart.classList.add("heart");
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.fontSize = Math.random() * 16 + 16 + "px";
      heart.textContent = "❤️";
      document.body.appendChild(heart);

      setTimeout(() => {
        heart.remove();
      }, 6000);
    }

    setInterval(createHeart, 300);
  </script>

</body>
</html>

 body {
      margin: 0;
       font-family: 'Poppins', sans-serif;
      background: #fff0f5;
      color: #333;
    }

    header {
      background: linear-gradient(to right, #234bb8, #b83131);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

   header h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3.5em;
      color: #fff;
    }

    section {
      padding: 30px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .fade-in {
  opacity: 0;
  animation: fade 2s ease forwards;
}

@keyframes fade {
  to {
    opacity: 1;
  }
}

    .photos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .photos img {
      width: 100%;
      height: 75%;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    .text-content {
      background: #ffe4e1;
      padding: 20px;
      border-radius: 10px;
      margin-top: 30px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .bible-verses {
  background: #fff5f8;
  padding: 25px;
  border-radius: 12px;
  margin-top: 40px;
  box-shadow: 0 3px 8px rgba(0,0,0,0.1);
}

.bible-verses h2 {
  text-align: center;
  color: #d63384;
  margin-bottom: 20px;
}

.bible-verses p {
  font-size: 1.1em;
  line-height: 1.6;
  margin-bottom: 20px;
}

    .languages {
      margin-top: 40px;
      text-align: center;
    }

    .languages h2 {
      margin-bottom: 15px;
      color: #ff4b91;
    }

    .languages p {
      font-size: 1.2em;
      line-height: 1.6;
    }

    footer {
      background: #ffd1dc;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      font-size: 0.9em;
    }

    
.heart {
      position: fixed;
      top: -50px;
      font-size: 24px;
      color: #ff6699;
      animation: fall 6s linear infinite;
      opacity: 0.8;
      z-index: 999;
    }

    @keyframes fall {
      0% {
        transform: translateY(-100px) rotate(0deg);
        opacity: 1;
      }
      100% {
        transform: translateY(100vh) rotate(360deg);
        opacity: 0;
      }
    }
