<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VCBOT – Ganhos Diários com Segurança</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to bottom right, #1e0037, #3f0066);
      color: #fff;
    }
    header, footer {
      background-color: #2e003e;
      color: #fff;
      padding: 30px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      color: #ffd700;
    }
    header p {
      font-size: 1.2rem;
    }
    .motivacional {
      background-color: #5a189a;
      color: #fff;
      padding: 20px;
      text-align: center;
      font-size: 1.5rem;
      font-weight: bold;
      border-top: 3px solid #ffd700;
      border-bottom: 3px solid #ffd700;
    }
    .section {
      background-color: #fff;
      color: #222;
      padding: 40px 20px;
      max-width: 900px;
      margin: 30px auto;
      border-radius: 10px;
      box-shadow: 0 0 30px rgba(255, 215, 0, 0.1);
    }
    h2 {
      color: #5a189a;
      font-size: 1.8rem;
      border-left: 6px solid #ffd700;
      padding-left: 12px;
      margin-bottom: 20px;
    }
    .valores {
      background-color: #eeeeff;
      padding: 20px;
      border-left: 5px solid #5a189a;
      margin-top: 20px;
      font-size: 1.1rem;
    }
    .cta-buttons {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
      flex-wrap: wrap;
    }
    .cta-buttons a {
      padding: 15px 30px;
      border-radius: 25px;
      background: linear-gradient(to right, #ffd700, #ff9900);
      color: #000;
      text-decoration: none;
      font-size: 1.1rem;
      font-weight: bold;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }
    .cta-buttons a:hover {
      transform: scale(1.05);
    }
    img.prova, img.acao-social {
      width: 100%;
      margin: 20px 0;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0,0,0,0.2);
      border: 2px solid #ffd700;
    }
    .calculator {
      background: #1a1a2e;
      color: #fff;
      padding: 25px;
      border-radius: 15px;
      max-width: 500px;
      margin: 30px auto;
      box-shadow: 0 0 25px #ffd700;
    }
    .calculator input {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: none;
      border-radius: 8px;
      font-size: 1.1em;
      background: #333;
      color: #fff;
    }
    .calculator button {
      width: 100%;
      padding: 12px;
      background: #ffd700;
      color: #000;
      border: none;
      border-radius: 8px;
      font-weight: bold;
      font-size: 1.1em;
      cursor: pointer;
    }
    .resultado {
      margin-top: 15px;
      background: #222;
      padding: 15px;
      border-radius: 10px;
      color: #fff;
      border: 1px solid #ffd700;
      font-size: 1.1em;
    }
    .resultado strong {
      color: #ffd700;
    }
    .divisoria {
      width: 100%;
      height: 6px;
      margin: 24px 0;
      display: flex;
      justify-content: center;
      gap: 6px;
    }
    .divisoria::before,
    .divisoria::after {
      content: "";
      display: block;
      width: 45%;
      height: 6px;
      border-radius: 3px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .divisoria::before {
      background: linear-gradient(90deg, #f9d71c, #f7c518);
    }
    .divisoria::after {
      background: linear-gradient(90deg, #6a0dad, #7b1fa2);
    }
  </style>
</head>
<body>

  <header>
    <h1>VCBOT: Ganhos Diários no Automático</h1>
    <p>Invista a partir de <strong>$30</strong> e receba lucros de até <strong>3.3% ao dia</strong> com segurança!</p>
  </header>

<section class="section calculator">
    <h2 style="text-align:center;">💵 Simule seus Rendimentos</h2>
    <input type="number" id="usd" placeholder="Digite quanto vai investir (mínimo $30)">
    <button onclick="calcular()">Calcular</button>
    <div id="resultado" class="resultado">Preencha o valor acima para simular.</div>
  </section>

  <div class="motivacional">
    "A única coisa que separa você da liberdade financeira é a decisão de começar."
  </div>

  <section class="section">
    <h2>💸 Faixas de Investimento e Lucro Diário</h2>
    <div class="valores">
      <p><strong>💰 De $30 a $99:</strong> 2.40% ao dia</p>
      <p><strong>💰 De $100 a $499:</strong> 2.60% ao dia</p>
      <p><strong>💰 De $500 a $1999:</strong> 2.80% ao dia</p>
      <p><strong>💰 Acima de $2000:</strong> 3.30% ao dia</p>
    </div>
    <p style="margin-top:20px;">Ganhos garantidos diariamente com total segurança. Seu dinheiro trabalha para você com operações de arbitragem em criptomoedas feitas por robôs inteligentes.</p>
  </section>

  <section class="section">
    <h2>🚀 Como Funciona a Plataforma</h2>
    <p>A VCBOT opera com robôs de arbitragem que compram e vendem criptomoedas automaticamente em diferentes corretoras, aproveitando variações de preço. Tudo é 100% automatizado, sem você precisar entender de mercado financeiro ou fazer análises.</p>
    <p>Você investe, e todos os dias vê seu saldo crescer com transparência e consistência. A plataforma garante os rendimentos com operações seguras e comprovadas.</p>
  </section>

  <section class="section">
    <h2>📱 Provas de Pagamento</h2>
    <img src="https://i.postimg.cc/tg0zWhsq/IMG-20250728-154502-970.jpg" class="prova">
    <img src="https://i.postimg.cc/VLVgLy1b/IMG-20250728-154656-148.jpg" class="prova">
    <img src="https://i.postimg.cc/4Ndwg4Cg/IMG-20250728-154926-819.jpg" class="prova">
  </section>

  <section class="section">
    <h2>🌍 Mais que Lucro: Um Investimento com Propósito</h2>
    <p>
      Quando você investe com a VCBOT, você não apenas faz seu dinheiro trabalhar para você — você também ajuda a transformar vidas reais.
    </p>

    <div class="divisoria"></div>

    <p>
      Parte dos lucros gerados pela plataforma é direcionada a <strong>projetos sociais que apoiam idosos, famílias carentes e comunidades em situação de vulnerabilidade</strong>. São ações que acontecem de verdade, com resultados visíveis.
    </p>

    <div class="divisoria"></div>

    <p>
      💜 A cada ativação de robô, você contribui diretamente com alimentos, medicamentos e dignidade para quem mais precisa. Você ganha, e o mundo também.
    </p>

    <div class="divisoria"></div>

    <p>
      ➕ Isso é mais do que um investimento. É fazer parte de uma causa com impacto direto e comprovado. Aqui, lucro e solidariedade caminham juntos!
    </p>

    <img src="https://i.postimg.cc/MHsDQNQN/IMG-20250728-154942-879.jpg" class="acao-social">
    <img src="https://i.postimg.cc/nrV2MpCq/IMG-20250728-155005-541.jpg" class="acao-social">
  </section>

  <section class="section">
    <h2>❓ Perguntas Frequentes</h2>

    <div style="background:#f8f8ff; padding:20px; border-left:5px solid #5a189a; border-radius:10px; margin-bottom:20px;">
      <p><strong style="color:#5a189a;">🔹 Qual o valor mínimo para investir?</strong><br>
      O investimento mínimo é de <strong>$30</strong>, acessível para qualquer pessoa iniciar.</p>
    </div>

    <div style="background:#f8f8ff; padding:20px; border-left:5px solid #5a189a; border-radius:10px; margin-bottom:20px;">
      <p><strong style="color:#5a189a;">🔹 Posso sacar todos os dias?</strong><br>
      Sim! Os saques são liberados diariamente a partir de $5, via Pix.</p>
    </div>

    <div style="background:#f8f8ff; padding:20px; border-left:5px solid #5a189a; border-radius:10px; margin-bottom:20px;">
      <p><strong style="color:#5a189a;">🔹 A VCBOT é confiável?</strong><br>
      Sim! A plataforma já possui milhares de usuários recebendo diariamente sem falhas. O sistema utiliza bots reais e arbitragem automatizada.</p>
    </div>

<div style="background:#f8f8ff; padding:20px; border-left:5px solid #5a189a; border-radius:10px; margin-bottom:20px;">
      <p><strong style="color:#5a189a;">🔹 Preciso indicar alguém?</strong><br>
      Não. Os lucros são 100% com base no seu investimento. Indicar é opcional e pode aumentar seus ganhos com bônus.</p>
    </div>

    <div style="background:#f8f8ff; padding:20px; border-left:5px solid #5a189a; border-radius:10px; margin-bottom:20px;">
      <p><strong style="color:#5a189a;">🔹 Como recebo os lucros?</strong><br>
      Os rendimentos são creditados diariamente no seu painel. Você pode solicitar saque a qualquer momento.</p>
    </div>

    <div style="background:#f8f8ff; padding:20px; border-left:5px solid #5a189a; border-radius:10px;">
      <p><strong style="color:#5a189a;">🔹 Funciona no celular?</strong><br>
      Sim! A plataforma é 100% online, acessível por celular, computador ou tablet.</p>
    </div>
  </section>

  <section class="section">
    <h2>💬 Fale com a Gente</h2>
    <p>Tem dúvidas? Quer começar agora com suporte? Clique e fale direto no WhatsApp!</p>
    <div class="cta-buttons">
      <a href="https://wa.me/5548991325944" target="_blank">📲 WhatsApp</a>
      <a href="https://www.vcbot.org/#/register?share_code=754543" target="_blank">✅ Criar Conta</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 VCBOT. Todos os direitos reservados.</p>
  </footer>

  <script>
    const cotacao = 5.56;
    function calcular() {
      const usd = parseFloat(document.getElementById('usd').value);
      const res = document.getElementById('resultado');

      if (isNaN(usd) || usd <= 0) {
        res.innerHTML = "<strong style='color:#ffd700;'>⚠️ Digite um valor válido em USD.</strong>";
        return;
      }

      if (usd < 30) {
        res.innerHTML = "<strong style='color:red;'>🚫 O valor mínimo para ativar o robô é $30.</strong>";
        return;
      }

      const brl = usd * cotacao;
      let porcentagem = 0;
      if (usd >= 30 && usd <= 99) porcentagem = 2.4;
      else if (usd >= 100 && usd <= 499) porcentagem = 2.6;
      else if (usd >= 500 && usd <= 1999) porcentagem = 2.8;
      else if (usd >= 2000) porcentagem = 3.3;

      const diaria = brl * (porcentagem / 100);
      const semanal = diaria * 7;
      const mensal = diaria * 30;
      const anual = diaria * 365;

      res.innerHTML =
        <strong>US$ ${usd.toFixed(2)}</strong> = <span style="color:#ffd700;">R$ ${brl.toFixed(2)}</span><br>
        📅 <strong>Diário:</strong> R$ ${diaria.toFixed(2)} (${porcentagem}% ao dia)<br>
        📆 <strong>Semanal:</strong> R$ ${semanal.toFixed(2)}<br>
        📅 <strong>Mensal:</strong> R$ ${mensal.toFixed(2)}<br>
        📈 <strong>Anual:</strong> R$ ${anual.toFixed(2)};
    }
  </script>

</body>
</html>
