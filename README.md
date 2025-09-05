# Apresenta-o-da-proposta-e-defini-o-dos-objetivos

Documento de Especificação de Requisitos do Sistema de Gerenciamento de Biblioteca
1. Introdução
Este documento descreve os requisitos do Sistema de Gerenciamento de Biblioteca (SGB), que visa facilitar o gerenciamento de livros, usuários e empréstimos em uma biblioteca. O sistema permitirá que bibliotecários e usuários gerenciem de forma eficiente o acervo e as transações de empréstimos.

2. Objetivo
O objetivo deste documento é fornecer uma visão clara e detalhada dos requisitos funcionais e não funcionais do SGB, servindo como guia para a equipe de desenvolvimento e stakeholders.

3. Escopo do Projeto
O SGB permitirá:

Cadastrar e gerenciar livros.
Cadastrar e gerenciar usuários.
Realizar empréstimos e devoluções de livros.
Consultar acervo e histórico de empréstimos.

4. Requisitos Funcionais

 - 4.1. Requisitos de Usuário
RF001: O sistema deve permitir que o usuário se cadastre fornecendo nome, email e senha.
RF002: O sistema deve permitir que o usuário faça login com email e senha.
RF003: O sistema deve permitir que o usuário busque livros por título, autor ou ISBN.
RF004: O sistema deve permitir que o usuário visualize detalhes de um livro (título, autor, ano de publicação, disponibilidade).
RF005: O sistema deve permitir que o usuário solicite o empréstimo de um livro disponível.
RF006: O sistema deve permitir que o usuário veja seu histórico de empréstimos.

 - 4.2. Requisitos de Administrador/Bibliotecário
RF007: O sistema deve permitir que o bibliotecário adicione novos livros ao acervo.
RF008: O sistema deve permitir que o bibliotecário edite informações de um livro existente.
RF009: O sistema deve permitir que o bibliotecário remova livros do acervo.
RF010: O sistema deve permitir que o bibliotecário registre um empréstimo de livro para um usuário.
RF011: O sistema deve permitir que o bibliotecário registre a devolução de um livro.

5. Requisitos Não Funcionais

 - 5.1. Desempenho
RNF001: O sistema deve ser capaz de atender a até 100 usuários simultâneos sem degradação de performance.
RNF002: As consultas de livros devem ser realizadas em até 2 segundos.

 - 5.2. Segurança
RNF003: O sistema deve proteger os dados dos usuários com criptografia.
RNF004: O acesso ao sistema deve ser controlado por autenticação de usuários.

 - 5.3. Usabilidade
RNF005: O sistema deve ter uma interface amigável e intuitiva.
RNF006: O sistema deve ser acessível em dispositivos móveis e desktop.

 - 5.4. Manutenção
RNF007: O sistema deve permitir fácil atualização e manutenção, sem necessidade de downtime significativo.

6. Conclusão
Este documento fornece uma visão abrangente dos requisitos necessários para o desenvolvimento do Sistema de Gerenciamento de Biblioteca. A equipe de desenvolvimento deve seguir esses requisitos para garantir que o sistema atenda às necessidades dos usuários e administradores, promovendo um ambiente de gerenciamento de biblioteca eficiente e eficaz.
