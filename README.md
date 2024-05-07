# Desafio: Criando um Sistema Bancário

## Objetivo Geral

Criar um sistema bancário com as operações: **sacar, depositar e visualizar extrato**.

## Desafio

Fomos contratados por um grande banco para desenvolver o seu novo sistema. Esse banco deseja modernizar suas operações e para isso escolheu a __linguagem Python__. Para a primeira versão do sistema devemos implementar apenas três operações: __depósito, saque e extrato__.

## Explicação das Operações

### Depósito

* Deve ser possível depositar valores positivos para a minha conta bancária. A primeira versão do projeto trabalha apenas com um __usuário__, dessa forma não precisamos nos preocupar em identificar qual é o número da __agência__ e __conta bancária__. Todos os depósitos devem ser armazenados em uma variável e exibidos na operação de extrato.

### Saque

* O sistema deve permitir realizar três saques diários com limite máximo de R$ 500,00 por saque. Caso o usuário não tenha saldo em conta, o sistema deve exibir uma mensagem informando que não será possível sacar o dinheiro por falta de saldo. Todos os saques devem ser armazenados em uma variável e exibidos na operação de extrato.

### Extrato

* Essa operação deve listar todos os depósitos e saques realizados na conta. No fim da listagem deve ser exibido o saldo atual da conta. Se o extrato estiver em branco, exibir a mensagem: Não foram realizadas movimentações.
Os valores devem ser exibidos utilizando o formato __R$ xxx.xx__, exemplo:
1500.45 = R$ 1500.45