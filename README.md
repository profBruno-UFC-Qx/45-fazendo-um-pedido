# Descrição

Neste exercício, você irá criar uma página web que seria usada supostamente para pedir a um fornecedor uma quantidade de itens para recompor seu estoque.

O objetivo deste exercício é praticar a manipulação da DOM usando JavaScript.

**Todas as alterações devem ser feitas nos arquivos já existentes**

* src/index.html -> quando for necessário alterar HTML
* src/css/estilo.css -> quando for necessário alterar CSS
* src/js/script.js -> quando for necessário alterar JavaScript

## Instruções:

1. Suponha que seu fornecedor tem uma lista de produtos em estoque, cada um com um nome e uma quantidade disponível.
2. Altere o arquivo **src/index.html** e crie um formulário para permitir que os usuários façam um pedido de produtos.
3. Adicione campos de entrada de texto para o nome e o e-mail do cliente, e um campo de seleção para o produto desejado.
4. Utilize HTML5 para adicionar atributos de validação, como required e type="email".
5. Usando JavaScript, ajuste o campo de quantidade para que o valor máximo seja a quantidade disponível do produto escolhido.
6. Adicione um botão de envio ao formulário.
7. Estilize o formulário com CSS para melhorar a aparência.

Exemplo de produtos em estoque (atualize com seus próprios valores):

```JavaScript
const produtosEmEstoque = [
  { nome: 'Produto 1', quantidade: 10 },
  { nome: 'Produto 2', quantidade: 5 },
  { nome: 'Produto 3', quantidade: 8 }
];
```


## Recomendações

**Certifique-se de validar seu código HTML usando um validador como o [W3C Markup Validation Service](https://validator.w3.org/), para garantir que seu código esteja sem erros e bem formado**.

**Experimente validar o seu código CSS em sites como:**

- <a href="https://jigsaw.w3.org/css-validator/" target="_blank">W3C CSS validation Service</a>
- <a href="https://beautifytools.com/css-validator.php" hreflang="en" target="_blank">Beatifytools CSS validator</a>
