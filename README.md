# Grana · Dinheiro se aprende mexendo

Educação financeira para jovens iniciantes. Site estático, sem backend de aplicação, cadastro, rastreadores adicionados ou dependências de instalação.

- 12 trilhas, 48 aulas e 108 atividades de oito tipos.
- Cinco simuladores, oficina de orçamento, desafios, glossário e fontes oficiais.
- Modo escuro inicial, modo claro, menu animado e ilustração ASCII com movimento controlável.
- Respostas, progresso, notas e valores dos simuladores ficam no `localStorage`. O progresso da versão anterior é preservado. O caderno pode ser exportado em JSON e as tabelas em CSV.

## Publicação

GitHub Pages: https://granainvestimentos.github.io/1/

O repositório usa `main` e a pasta raiz em Settings → Pages → Deploy from a branch. Mantenha `index.html`, os arquivos JS/CSS e as pastas `fonts` e `assets` na raiz. O arquivo `.nojekyll` evita processamento desnecessário pelo Jekyll.

Para testar localmente, execute `python3 -m http.server 4173` nesta pasta e abra `http://localhost:4173`.

## Arquivos

- `content.js`: conteúdo original das 12 trilhas, glossário, desafios e referências.
- `curriculum.js`: aprofundamentos, técnicas, casos de aplicação e atividades.
- `app.js`: navegação, atividades, cálculos e armazenamento local.
- `style.css`: tema, layout responsivo, animações e impressão.
- `assets/ascii-art-source.png`: imagem gerada da opção visual escolhida; o navegador exibe apenas sua região de ilustração e anima essa textura.
- `assets/icons`: ícones Phosphor Light, com licença MIT.
- `fonts`: fontes locais DM Sans e Manrope, com suas licenças OFL.

## Informação educativa

Os números de exemplos e simuladores são fictícios. Fórmulas e simplificações são exibidas junto ao resultado. As referências principais são Banco Central, CVM, IBGE, Tesouro Direto, FGC e Receita Federal. Não há cotações ao vivo ou previsões de retorno. Consulte regras, custos e tributos vigentes antes de uma decisão real.

A pesquisa original não integra a publicação. O site mostra somente contagens agregadas e explica que as opções admitiam múltipla escolha.
