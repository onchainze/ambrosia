# Ambrosia

Assistente culinário da família Santos Guerra: app web num único ficheiro (`index.html`) para planear as refeições da semana, em português.

## Funcionalidades
- Receitas por tipo (Carne, Peixe, Sopa, Massa e arroz, Vegetariano, Pequeno-almoço, Sobremesa)
- Pesquisa por receita ou ingrediente, e filtros por tempo, calorias, proteína, açúcar e vegetariano
- Visualização em cartões grandes, médios, pequenos ou em lista
- Informação nutricional aproximada por pessoa
- Plano semanal (pequeno-almoço, almoço e jantar), com sugestão automática
- Lista de compras automática, por secção do supermercado
- Exportar receitas e lista de compras em texto, e o calendário e a lista em PDF ou imagem
- Funciona no telemóvel e pode ser adicionada ao ecrã principal

Os dados (plano, favoritos, lista de compras, forma de visualização) ficam guardados no navegador de cada aparelho.

## Como publicar com GitHub Pages
1. Crie um repositório **público** no GitHub e carregue todos os ficheiros desta pasta.
2. Abra **Settings > Pages**.
3. Em "Build and deployment", escolha **Deploy from a branch**, a branch **main** e a pasta **/ (root)**, e guarde.
4. Ao fim de um ou dois minutos, a app fica em `https://O-SEU-UTILIZADOR.github.io/NOME-DO-REPOSITORIO/`.

## Atualizar
Substitua o `index.html` no repositório (Add file > Upload files, com o mesmo nome). A página atualiza sozinha.

## Fotografias das receitas (opcional)
1. Guarde as fotos na pasta `fotos`, uma por receita, com o id da receita, por exemplo `p-bacalhau-bras.jpg` (cerca de 800 px de largura).
2. No `index.html`, mude `const USAR_FOTOS=false;` para `true`.

Use apenas fotografias suas ou com licença livre, e indique o autor quando a licença o pedir.

## Receitas e fontes
As receitas são versões em português escritas para esta app, com valores nutricionais aproximados.
As que indicam uma fonte (Jamie Oliver, Pingo Doce) são inspiradas nos pratos dessas fontes, com ligação para a receita original no detalhe da receita. O texto das receitas originais não está incluído.
