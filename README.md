# nerd.virgem.com.br
sou.muito.virgem.com.br
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Correio Elegante 💌</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #ffc0cb, #ffe4e1);
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 20px;
    }
    .card {
      background-color: white;
      border-radius: 20px;
      padding: 30px;
      box-shadow: 0 0 20px rgba(0,0,0,0.1);
      text-align: center;
      max-width: 400px;
      width: 100%;
    }
    h1 {
      color: #d6336c;
      margin-bottom: 20px;
    }
    p.enigma {
      font-size: 18px;
      margin-bottom: 20px;
    }
    input {
      padding: 10px;
      width: 100%;
      border: 2px solid #d6336c;
      border-radius: 8px;
      font-size: 16px;
      margin-bottom: 15px;
    }
    button {
      background-color: #d6336c;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 10px;
      font-size: 16px;
      cursor: pointer;
    }
    #mensagem {
      display: none;
      margin-top: 20px;
      color: #d6336c;
      font-weight: bold;
      font-size: 16px;
      text-align: left;
      white-space: pre-wrap;
    }
    .heart {
      font-size: 30px;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="heart">❤️</div>
    <h1>Correio Elegante</h1>
    <p class="enigma">O que é capaz de viver no céu, na água e na terra... e que eu simplesmente amo?</p>
    <input type="text" id="resposta" placeholder="Digite sua resposta..." />
    <button onclick="verificarResposta()">Ver Mensagem</button>
    <div id="mensagem">
      não acredito que vc acertou a senha 😭🦆 era “pato” mesmo kkkkkkk
isso já prova que cê me conhece um pouco demais 👀💛 ou que meu amor por essas criaturinhas malucas é real demais kkkkk
sério, eu sou nerdola e virjão o suficiente pra fazer um programa só pra isso 🤓💻

mas yumi... essa mensagem aqui é mais do que só umas risadas aleatórias 😶‍‍🌫️

eu curto demais essa nossa relação maluca de amor e ódio 😵‍💫💘
tipo assim: uma hora cê quer conversar, rir, brincar comigo… outra hora parece que quer me matar com um olhar kkkkk 😅🔪
tem dia que me trata como se eu fosse importante, outro como se eu tivesse te devendo R$200 e ainda derrubado café no seu tênis favorito 🫠
tem hora que me chama de nego 🥰, outra de escravo 😭✊🏾
e eu fico tipo: se decide garota, prra* 😵‍💫😂*

e mesmo assim, eu continuo aqui, gostando de vc.
porque, por mais que vc tenha esse jeito CONFUSA, é real. e é seu jeito — esse jeitinho 8 ou 80 ⚖️💥, impulsiva, imprevisível, mas única.
e quer saber? eu gosto disso. gosto de vc. gosto da forma como vc bagunça minha mente, mas ainda assim me dá vontade de ficar por perto 💘

só que, confesso, sinto falta daquele anjinho que vc tava sendo há um tempo atrás 😇
ACHO QUE VOU EMPURRAR REMÉDIO DE ESTRESSE EM VC DENOVOOO 💊😤

às vezes eu fico bolado pensando se falei algo errado, se fiz alguma besteira, ou se vc só cansou de mim 🥲
pode ser viadagem minha também, mas precisava abrir isso contigo... porque eu não sou de ignorar quem eu gosto de verdade.

e vou contar uma coisa que tá entalada faz tempo kkkkk 🫣
lembra daquele dia da aula da Itamara, dos cachorros? 🐶
então... eu SABIA que vc tinha pit bull 🐾
mas mesmo assim inventei aquele assunto só pra puxar conversa contigo 🫢💬
foi na coragem total, mas eu queria muito falar contigo.
e olha, não me arrependo nem um pouco.

imagina se eu sentisse por vc o mesmo ranço que tenho da Raquel? 😭 misericórdia, ia ser guerra todo dia igual final de novela mexicana kkkkk 🎭📺
mas não… graças a Deus não é assim.
porque o que eu sinto por vc é totalmente o oposto disso. é leve, é sincero, é de verdade 😌❤️‍🔥

eu gosto MUITO de vc.
não tô dizendo isso esperando que vc diga o mesmo, mas porque eu precisava que vc soubesse.
não quero ser só aquele cara que vc lembra quando bate tédio ou quando quer dar risada.
quero ser alguém que tá ali do seu lado e soma.
tipo quando os seus cachorros assassinam alguma coisa que vc gosta, tipo seu livro ou o presente da Cibine 💞🐾

não tô te cobrando, nem forçando. só abrindo minha caixa torácica pra escrever essa budega.
foi mó difícil programar essa porra, então lê direito, sua doida kkkkk 💻😅

💬💗🧠🫀💛😵‍💫😳💘🦆✨🌙💞💬💗
    </div>
  </div>

  <script>
    function verificarResposta() {
      const resposta = document.getElementById('resposta').value.trim().toLowerCase();
      if (resposta === 'pato') {
        document.getElementById('mensagem').style.display = 'block';
      } else {
        alert('Ops! Resposta errada. Tente novamente.');
      }
    }
  </script>
</body>
</html>
