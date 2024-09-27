# Trabalho-de-Estoque
IFES-SISTEMAS-DE-INFORMACAO 
- PROG 2
- TURMA V06

# Sempre utilize funções. Uma função para cada funcionalidade.
# Não esqueça de usar uma variável para o tamanho do vetor.

# TEMA 3: SISTEMA DE ESTOQUE
## Crie um sistema para gerenciar o estoque de uma empresa. Seu sistema deve ter:
- Estrutura Data, com dia, mês e ano.
- Estrutura Produto, que possui código, nome, preço, quantidade em estoque e data
de validade (struct Data acima).
Seu sistema conterá um vetor de Produto e deve possuir as seguintes operações:
- Inserir produto: ler todos os dados de Data e Produto e inserir no vetor. Não deixar
inserir código de produto repetido.
- Pesquisar por código: pedir o código do produto e pesquisar no vetor, imprimindo
todos os dados de Produto e Data.
- Pesquisar por nome: pedir o nome do produto e pesquisar no vetor, imprimindo
todos os dados de Produto e Data.
- Atualizar preço: pedir o código do produto e a porcentagem de aumento ou
desconto. Pesquisar o código do produto no vetor e aplicar o aumento ou desconto
no preço.
- Maior preço: pesquisar qual é o produto com maior preço e mostrar todos os dados
de Produto e Data.
- Excluir: pedir o código do produto e excluir do vetor.
- Listar: mostrar todas os produtos e seu respectivo preço.

OBS: Reutilize a função pesquisar por código. Ela será utilizada pelas funções
inserir, aumentar preço, aplicar desconto e excluir.
Para isso seu sistema deve possuir o seguinte menu:

SISTEMA DE ESTOQUE

1 – Inserir produto

2 – Pesquisar por código

3 – Pesquisar por nome

4 – Atualizar preço

5 – Maior preço

6 – Excluir

7 - Listar

0 – Sair

Escolha sua opção
