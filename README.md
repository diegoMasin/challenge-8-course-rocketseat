# Desafio 8 - Curso GoStack Rocketseat

```Seguindo o template proposto, criar as seguintes funcionalidades no frontend:```
- Listar os produtos da fake API: Sua página Dashboard deve ser capaz de exibir uma listagem através de uma tabela, com os campos title, image_url e price.
  - Dica: Você pode utilizar a função Intl para formatar os valores. Dentro da pasta utils no template você encontrará um código para te ajudar.

- Adicionar itens ao carrinho: Em toda sua aplicação, você deve utilizar o Contexto chamado cart que deixamos disponível. Você vai precisar completar as funcionalidades dentro de hooks/cart.tsx para que você consiga adicionar itens ao carrinho.
  - Dica: No seu contexto de carrinho, utilize uma propriedade chamada quantity para controlar quantos desse item existem no seu carrinho.
  - Dica 2: Caso um produto que você está adicionando já exista no carrinho, apenas altere a quantidade dele no seu contexto para evitar itens duplicados.

- Exibir itens do carrinho: Na página Cart você deve exibir todos os itens do carrinho, junto com a quantidade, valor único, valor subtotal dos itens e total de todos os items.
- Aumentar quantidade de itens do carrinho: Na página Cart você deve permitir que o usuário aumente a quantidade de itens do mesmo produto, para isso você pode utilizar a função increment dentro do seu contexto em /src/hooks/cart.tsx.
- Diminuir quantidade de um item do carrinho: Na página Cart você deve permitir que o usuário decremente a quantidade de itens do mesmo produto, para isso você pode utilizar a função decrement dentro do seu contexto em /src/hooks/cart.tsx.
- Exibir valor total dos itens no carrinho: Tanto na página Dashboard, quanto na página Cart você deve exibir o valor total de todos os itens que estão no seu carrinho.

##### Executar **_yarn test_** para avaliar as diretrizes de avaliação.

### Instalação Local
Importante. Alterar na api, o base_url, de localhost para o seu ip local, se utilizando emulador android.
- git clone https://github.com/diegoMasin/desafio-8-curso-rocketseat.git
- execute no terminal dentro da pasta do projeto: **yarn**
Obs: Instale o yarn no seu sistema operacional, se caso não tenha.
- para rodar o projeto execute no terminal: **yarn start** e em um terminal paralelo, **yarn android**
Obs: se o emulador não abrir automaticamente, execute-o antes da linha de cima.
