# Projeto de Sistema de Transação em Python

Este projeto é uma implementação de um sistema simples de transações bancárias, construído em Python, com integração ao banco de dados PostgreSQL. Ele foi desenvolvido com fins educacionais, para explorar o uso de Python em um contexto de interação com banco de dados relacional.

## Características

O sistema permite execcutar várias operações bancárias, tais como:

* Depósitos;
* Saques;
* Consulta de informações da conta;
* Consulta de saldo;
* Visualização do extrato bancário.

  As transações são armazenadas em um banco de dados PostgreSQL, permitindo que o histórico de transações seja preservado e consultado.

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
