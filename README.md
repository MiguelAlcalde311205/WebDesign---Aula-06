# Web Design - Aula 06

Projeto de exercício de Web Design contendo um layout estático com HTML e CSS.

## Descrição

Este repositório contém uma página estática de exemplo criada como parte da "Aula 06" de um curso/prática de Web Design. O objetivo é demonstrar layout responsivo, variáveis CSS, componentes (botões, cards, formulário) e técnicas modernas de estilo (frosted glass, animações simples, clip-path, aspect-ratio).

## Estrutura do projeto

- `index.html` — Documento HTML principal com a marcação das seções (header, hero, sobre, habilidades, projetos, contato e footer).
- `style.css` — Folha de estilos principal. Contém variáveis em `:root`, estilos responsivos e componentes reutilizáveis.

## Como usar

Opções rápidas para visualizar o projeto localmente:

1. Abrir diretamente no navegador:

   - Abra o arquivo `index.html` com um navegador moderno (Chrome, Firefox, Edge, Safari).

2. Servir localmente (recomendado para evitar problemas com recursos relativos):

   - Usando Python 3 (porta 8000):

     ```bash
     python3 -m http.server 8000
     ```

     Em seguida, abra `http://localhost:8000` no navegador.

   - Usando o Live Server do VS Code (extensão): clique com o botão direito em `index.html` e escolha "Open with Live Server".

## Tecnologias

- HTML5
- CSS3 (variáveis CSS, Flexbox, Grid, media queries)

## Notas sobre o estilo (`style.css`)

- Variáveis globais estão definidas em `:root` para facilitar ajustes de cores, tipografia e espaçamentos.
- O header é fixo e usa `backdrop-filter` para um efeito de vidro fosco (nem todos os navegadores antigos suportam essa propriedade).
- O layout é responsivo com breakpoints em 768px e 480px.
- Foram usadas propriedades modernas (por exemplo, `aspect-ratio`, `clip-path`, `filter: drop-shadow`) para enriquecer o visual.

## Próximos passos sugeridos

- Adicionar um menu hambúrguer e interações com JavaScript para dispositivos móveis.
- Incluir ícones (por exemplo, Font Awesome) e otimizar imagens.
- Adicionar testes de acessibilidade e checagens de contraste de cor.

## Licença

Conteúdo criado para fins educacionais. Sinta-se à vontade para reutilizar ou adaptar para projetos pessoais.
