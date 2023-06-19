<h1 align="center">
   Controle Financeiro 💵
</h1>


## :rocket: Sobre o projeto

Este site de controle financeiro permite o registro de receitas e despesas, além de oferecer a funcionalidade de alternar entre temas claro e escuro. Para fazer os registros, o usuário deve fornecer o nome e o valor de cada receita ou despesa. Todos os registros são adicionados a uma lista de transações, que inclui o nome, o valor e uma etiqueta colorida ao lado para indicar se é uma receita (verde) ou uma despesa (vermelha).

A cada registro, é feito um balanço no saldo atual. As receitas são somadas ao saldo atual e ao valor total das receitas, enquanto as despesas são subtraídas do saldo atual e somadas ao valor total das despesas.

Todos os registros são armazenados no armazenamento local do navegador (localStorage), garantindo que eles permaneçam salvos mesmo se a página for recarregada. Para excluir um registro, basta passar o mouse sobre ele na lista de transações, o que revelará um botão no canto esquerdo para removê-lo. Após a exclusão, o balanço do saldo atual, das receitas e das despesas é recalculado, sem considerar o registro excluído.

## :computer: Tecnologias usadas:

- `Javascript`
- `HTML`
- `CSS`
