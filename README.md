<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Mateus Dantas Medeiros | Desenvolvedor Backend</title>
  <style>
    :root {
      --bg-top: #0b1220;
      --bg-bottom: #05070d;
      --card: rgba(255, 255, 255, 0.05);
      --border: rgba(255, 255, 255, 0.12);
      --text: #e8edf5;
      --muted: #9aa7bd;
      --accent: #3b82f6;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      min-height: 100vh;
      font-family: "Segoe UI", system-ui, -apple-system, Roboto, Arial, sans-serif;
      color: var(--text);
      background: linear-gradient(180deg, var(--bg-top), var(--bg-bottom));
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 24px 16px;
      line-height: 1.6;
    }

    main {
      width: 100%;
      max-width: 760px;
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 40px 36px;
    }

    h1 {
      font-size: 1.9rem;
      margin-bottom: 16px;
    }

    h1 span { color: var(--accent); }

    p { margin-bottom: 14px; }

    strong { color: #ffffff; }

    .linha .rotulo { color: var(--muted); }

    h2 {
      margin-top: 28px;
      margin-bottom: 14px;
      font-size: 1.1rem;
      color: var(--muted);
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.08em;
    }

    .botoes {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .botao {
      display: inline-block;
      padding: 10px 20px;
      border-radius: 8px;
      font-size: 0.85rem;
      font-weight: 700;
      letter-spacing: 0.06em;
      text-decoration: none;
      color: #ffffff;
      transition: transform 0.15s ease, opacity 0.15s ease;
    }

    .botao:hover { transform: translateY(-2px); opacity: 0.9; }

    .linkedin  { background: #0a66c2; }
    .instagram { background: #e4405f; }
    .github    { background: #24292f; }

    @media (max-width: 520px) {
      main { padding: 28px 20px; }
      h1 { font-size: 1.5rem; }
    }
  </style>
</head>
<body>
  <main>
    <h1>Olá, meu nome é <span>Mateus Dantas Medeiros</span>!</h1>

    <p>
      <strong>Estudante de Análise e Desenvolvimento de Sistemas</strong> na UNIASSELVI,
      com foco em <strong>Desenvolvimento Backend</strong>. Venho de uma trajetória em
      suporte técnico de informática e hoje busco meu primeiro estágio na área.
    </p>

    <p class="linha"><span class="rotulo">Linguagens:</span> <strong>Python</strong>.</p>

    <p class="linha">
      <span class="rotulo">Conceitos:</span>
      <strong>Programação Orientada a Objetos</strong>,
      <strong>Estruturas de Dados</strong>,
      <strong>Algoritmos</strong> e
      <strong>Modelagem de Dados</strong>.
    </p>

    <p class="linha">
      <span class="rotulo">Outros:</span>
      Excel Avançado, Power Pivot, Dashboards, Suporte Técnico.
    </p>

    <h2>Contatos</h2>
    <div class="botoes">
      <!-- Troque pelos seus links reais -->
      <a class="botao linkedin" href="https://www.linkedin.com/in/mateus-dantas-medeiros" target="_blank" rel="noopener">LINKEDIN</a>
      <!-- Descomente quando criar o GitHub e/ou quiser divulgar o Instagram:
      <a class="botao github" href="https://github.com/SEU-USUARIO" target="_blank" rel="noopener">GITHUB</a>
      <a class="botao instagram" href="https://instagram.com/SEU-USUARIO" target="_blank" rel="noopener">INSTAGRAM</a>
      -->
    </div>
  </main>
</body>
</html>
