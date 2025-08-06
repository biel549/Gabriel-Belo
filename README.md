<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
</head>
<body>
  <header>
    <h1>Biel Ferreira</h1>
    <nav>
      <a href="#sobre">Sobre</a> |
      <a href="#projetos">Projetos</a> |
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <main>
    <section id="sobre">
      <h2>Sobre mim</h2>
      <p>Oi! Eu sou o Biel, um desenvolvedor front-end em aprendizado constante. Gosto de criar sites modernos e funcionais, focados na experiência do usuário e visual atrativo. Estudo HTML, CSS e JavaScript, e estou sempre buscando novos desafios para evoluir.</p>
    </section>

    <section id="projetos">
      <h2>Projetos</h2>
      <ul>
        <li>
          <strong>Site Loja de Games</strong><br />
          Um site simples com HTML e CSS para venda de jogos, com design responsivo e visual moderno.<br />
          <a href="https://github.com/seuusuario/lojagames" target="_blank">Ver no GitHub</a>
        </li>
        <li>
          <strong>Portfólio Pessoal</strong><br />
          Meu próprio portfólio criado com HTML, CSS e JavaScript para mostrar meus projetos e habilidades.<br />
          <a href="https://github.com/seuusuario/portfolio" target="_blank">Ver no GitHub</a>
        </li>
        <li>
          <strong>Jogo Quiz JS</strong><br />
          Jogo de perguntas e respostas feito com JavaScript para treinar lógica e DOM.<br />
          <a href="https://github.com/seuusuario/jogoquiz" target="_blank">Ver no GitHub</a>
        </li>
      </ul>
    </section>

    <section id="contato">
      <h2>Contato</h2>
      <form onsubmit="alert('Mensagem enviada! Obrigado por entrar em contato.'); return false;">
        <label for="nome">Nome</label><br />
        <input type="text" id="nome" name="nome" placeholder="Seu nome" required /><br /><br />

        <label for="email">Email</label><br />
        <input type="email" id="email" name="email" placeholder="seuemail@email.com" required /><br /><br />

        <label for="mensagem">Mensagem</label><br />
        <textarea id="mensagem" name="mensagem" rows="5" placeholder="Escreva aqui..." required></textarea><br /><br />

        <button type="submit">Enviar</button>
      </form>
    </section>
  </main>
</body>
</html>
