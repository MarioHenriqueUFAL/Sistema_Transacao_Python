# Projeto de Sistema de Transação em Python

Este projeto é uma implementação de um sistema simples de transações bancárias, construído em Python, com integração ao banco de dados PostgreSQL. Ele foi desenvolvido como parte do bootcamp [Potência Tech powered by iFood | Ciência de Dados com Python](https://www.dio.me/bootcamp/potencia-tech-powered-ifood-ciencias-de-dados-com-python), promovido pela [dio](https://www.dio.me/), com o objetivo de explorar o uso de Python em um contexto de interação com banco de dados.

## Requisitos do Projeto

  Os requisitos específicos do projeto eram os seguintes:
  
  * **Operação de Depósito**: O usuário só pode depositar valores positivos na conta;
  * **Operação de Saque**: O sistema deve permitir realizar 3 saques diários com limite máximo de R$ 500,00 por saque. Se o usuário não tem saldo na conta, o sistema deve exibir uma mensagem informando que não é possível sacar o dinheiro por saldo insuficiente. Todos os saques devem ser armazenados e exibidos na operação de extrato;
  * **Operação de Extrato**: O sistema deve listar todos os depósitos e saques realizados na conta em uma data especificada. No fim da lista deve ser exibido o saldo atual da conta. Se o extrato estiver em branco, o sistema deve exibir a mensagem: "Não foram realziadas movimentações!".

## Características

  O sistema permite executar operações de saque, depósito e visualização de extrato, conforme especificado nos requisitos do projeto. As transações são armazenadas em um banco de dados PostgreSQL, permitindo que o histórico de transações seja preservado e consultado. Adicionalmente, o sistema é capaz de realizar o cadastro de clientes e contas bancárias.

## Arquitetura e Design de Código

  O sistema é estruturado em torno de uma classe 'ContaBancaria' que representa uma conta bancária individual. Esta classe possui métodos para realizar as operações bancárias listadas acima.
  
  Os detalhes de conexão com o banco de dados são encapsulados dentro da classe 'ContaBancaria', que cria uma conexão com o banco de dados PostgreSQL ao ser instanciado e fornece métodos para executar consultas SQL.
  
  Além disso, a estrutura do código permite a reutilização de consultas SQL e a abstração de detalhes específicos do banco de dados. Cada função tem uma única responsabilidade, tornando o código mais legível e com maior facilidade para operações de manutenção.

## Aprendizado

  Este projeto permitiu um excelente aprendizado e prática de várias habilidade e conceitos importantes de programação, incluindo:

  * Orientação a objetos em Python;
  * Conexão e interação com um banco de dados PostgreSQL;
  * Execução de consultas SQL em Python;
  * Gestão de exceções em Python;

  Além disso, o projeto permitiu colocar em prática a habilidade de desenvolvimento de modelagem de dados, tendo sido construídos os modelos conceituais e lógicos do sistema.

## Melhorias Futuras

  Embora o sistema seja funcional, existem várias possibilidade para expandir e melhorar o projeto, que poderiam ter sido aplicadas. Tais como:

  * Adicionar um sistema de autenticação de usuários;
  * Melhorar a segurança do sistema através da criptografia das credenciais do banco de dados;
  * Implementar uma interface gráfica de usuário (GUI) para tornar o sistema mais fácil de usar.
