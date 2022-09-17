# Desafio Refinando um Projeto Conceitual de Banco de Dados - E-commerce (Replicar e Melhorar)

Repositório referente à modelagem de esquema conceitual para um cenário de E-commerce, a partir de um contexto reduzido apresentado em aula. 

## Narrativa:

- **Escopo:** venda de produtos > produto, estoque, fornecedor, cliente, pedido;

- **Produto:** os produtos são vendidos por uma única plataforma online e podem ter vendedores distintos (terceiros). Além disso, cada produto possui um fornecedor e o mesmo pedido pode ter um ou mais produtos;

- **Cliente:** pode ser cadastrado no site com CPF ou CNPJ. O endereço do cliente irá determinar o valor do frete e um cliente pode comprar mais de um pedido. O cliente tem período
de carência para devolução do produto;

- **Pedido:** é criado pelo cliente e possui informações de
compra, endereço e status da entrega. O pedido pode conter um ou mais produtos e poderá ser cancelado.

## Desafio:

- Cada conta de cliente pode ser PJ ou PF, mas não
pode ter as duas informações (vinculado um único e-mail para cada tipo de conta);

- Cada cliente pode ter cadastrado mais de uma forma de
pagamento;

- A entrega deve possuir status e código de rastreio.


## Informações:

- Optei pelo uso da ferramenta MySQL Workbench para a elaboração deste primeiro projeto conceitual de banco de dados, que se baseia nos conhecimentos adquiridos até o momento;
 
- Apresentação em PNG conforme informado no desafio;

- Intuito de futuras melhorias com base no desenvolvimento do aprendizado durante a jornada.

# :sparkles:👩🏽‍💻:sparkles: