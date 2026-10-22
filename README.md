# Biblioteca Digital Acessível

Este projeto é uma página web simples e responsiva criada para catalogar e organizar livros e materiais de estudo. O foco principal do desenvolvimento foi a aplicação prática de conceitos de **Acessibilidade Digital (a11y)**.

## 🗂️ Estrutura de Arquivos
- `index.html`: Estrutura semântica e conteúdo da página.
- `style.css`: Estilização, layout (Flexbox e Grid) e regras de responsividade.
- `README.md`: Documentação e descrição do projeto.

## 🚀 Como executar o projeto
1. Baixe ou clone os arquivos para uma pasta no seu computador.
2. Certifique-se de que os arquivos `index.html` e `style.css` estão no mesmo diretório.
3. Dê um duplo clique no arquivo `index.html` para abri-lo diretamente no seu navegador padrão.

## ♿ Boas Práticas de Acessibilidade Aplicadas
Para garantir que a plataforma seja acessível ao maior número de usuários, as seguintes regras foram implementadas:

1. **Títulos organizados hierarquicamente:** Uso rigoroso e semântico das tags `<h1>`, `<h2>` e `<h3>`.
2. **Textos curtos e objetivos:** Parágrafos diretos para facilitar a leitura e a compreensão (carga cognitiva reduzida).
3. **Fonte legível:** Uso da família tipográfica "sans-serif" (Arial/Helvetica) com tamanho de fonte de `16px` e um bom espaçamento entre linhas (`line-height: 1.6`).
4. **Contraste adequado:** Cores de fundo claras combinadas com textos escuros (`#1A1A1A`) e um tom de azul (`#0056B3`) validado para alto contraste, ajudando pessoas com baixa visão ou daltonismo.
5. **Imagens com descrição:** Todas as imagens possuem o atributo `alt` detalhando o contexto visual da foto para leitores de tela.
6. **Botões com nomes claros:** Os botões possuem atributos `aria-label` que descrevem explicitamente a ação ("Ver detalhes do livro X").
7. **Espaçamento adequado:** Uso de `gap` em Grid e Flexbox, além de margens que impedem elementos de ficarem "grudados".
8. **Menu com navegação previsível:** Links intuitivos utilizando âncoras para percorrer a mesma página (`#id`), e destaques visuais (outline) para usuários que navegam pela tecla `Tab`.
9. **Zero animações desnecessárias:** Evitou-se o uso de efeitos piscantes, sliders complexos ou movimentos que podem causar tontura ou desconforto ao usuário.
