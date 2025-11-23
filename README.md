
📽️ Base de Conhecimento de Filmes e Séries
Este é um projeto simples de Base de Conhecimento desenvolvido em HTML, CSS e JavaScript puro (Vanilla JS), focado em exibir e permitir a busca de filmes e séries a partir de um arquivo de dados estático em formato JSON.

✨ Visão Geral do Projeto
O objetivo principal é demonstrar a leitura e manipulação de dados em JavaScript para criar uma interface de usuário dinâmica, onde o conteúdo é renderizado a partir de uma fonte de dados externa (data.json) e pode ser filtrado através de uma barra de pesquisa.

🛠️ Tecnologias Utilizadas
HTML5: Estrutura base da página (index.html).

CSS3: Estilização e layout da interface (style.css).

JavaScript (ES6+): Lógica de busca e manipulação do DOM (scrpit.js).

JSON: Fonte de dados estruturada para filmes e séries (data.json).

📂 Estrutura de Arquivos
O projeto está organizado na seguinte estrutura:

base-de-conhecimento/
├── index.html          # Estrutura HTML da página.
├── style.css           # Estilos visuais da aplicação.
├── scrpit.js           # Lógica de busca e renderização de cards.
└── data.json           # Base de dados com filmes e séries.
⚙️ Funcionalidades
Carregamento de Dados Assíncrono: Ao iniciar a busca pela primeira vez, o scrpit.js utiliza a função fetch para carregar o conteúdo do arquivo data.json.

Busca Dinâmica: O usuário pode digitar um termo no campo de busca. A função iniciarBusca() filtra os dados, procurando pelo termo no nome ou na descricao de cada item (ignorando maiúsculas/minúsculas).

Renderização de Cards: A função renderizarCards() limpa o container de resultados e exibe os filmes/séries filtrados como cards (<article class="card">), mostrando:

Título (<h2>)

Ano de Lançamento (<p>)

Descrição (<p>)

Link para "Saiba mais" (<a>)

🔍 Como Usar (Localmente)
Para visualizar e testar o projeto:

Clone o Repositório (ou baixe os arquivos para uma pasta).

Abra o index.html em seu navegador.

O campo de busca estará disponível no topo.

Clique em "Buscar" (com o campo vazio) para carregar todos os itens do data.json, ou digite um termo (ex: "terror", "2026", "Deadpool") e clique em Buscar para filtrar.

🚀 Melhorias Futuras
O projeto atual é uma base e pode ser expandido com as seguintes melhorias:

Filtro por Tags: Adicionar botões ou dropdowns para filtrar por tags (Ficção Científica, Série, Filme).

Renderização Inicial: Carregar e exibir todos os filmes automaticamente ao carregar a página (sem precisar clicar em "Buscar" primeiro).

Tratamento de Tags: Incluir as tags do JSON na estrutura do card para exibi-las na interface.

Melhoria na UX da Busca: Implementar a busca em tempo real (oninput) em vez de depender apenas do clique no botão.

Estilização Responsiva: Aperfeiçoar o CSS para garantir uma excelente experiência em dispositivos móveis.
