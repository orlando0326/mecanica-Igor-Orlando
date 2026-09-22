# mecanica-Igor-Orlando
Descritivo do que a aplicação precisa fazer:
Responsáveis: Igor; Orlando

## Front
- lista das ações necessárias no front ( telas, e comportamento)
  -Desenvolver um site que utilize varias ferramentas para auxiliar as pessoas durante o uso
  por exemplo: login, "Esqueci a senha" e Tabelas.
  
  -No que iremos utilizar, vamos usar um sistema de Login para cadastrar um cliente e fazer validação caso Falha, 
  nome do usuário logado e uma forma de acessar os demais recursos, assim como uma maneira de sair do sistema.

  -Seu Comportamento será: Guardar informações e criptografalas ao banco de dados  
##
Backend e banco
- Lista dos controllers
  Veiculos, Agendamento, Cliente
  
- Lista das Entidades e seus relacionamentos
  Cliente e Veiculos são ligados a Agendamento
  
-Agendamento: nome, e-mail, contato, hora

-Cliente: Nome, e-mail, numero, id, idagendamento

-Veículos: Nome, problema, id, idAgentamento

- Lista de Rotas

## Contextualização:

A oficina mecânica mecanica-nome1-nome2 não tem sistema informatizado. Tudo é controlado manualmente, e isso gera problemas: agendamentos perdidos, informações duplicadas e dados guardados de forma insegura. O CPF dos clientes, por exemplo, fica exposto, o que pode fazer a empresa descumprir a LGPD.

Por isso, o gestor contratou a equipe (Igor e Orlando) para criar um software que organize os agendamentos e o cadastro de clientes e veículos. Ele pediu três coisas principais: login com tempo de expiração, proteção dos dados sensíveis e documentação técnica (requisitos e o DER) para facilitar a manutenção no futuro.

Resumindo: o objetivo é trocar o controle no papel por um sistema web organizado, seguro e fácil de manter.

## Equipamentos Ultilizados:

## Para o backend (a parte que faz o sistema funcionar por trás):

C# — linguagem principal para criar a API, o login e a criptografia dos dados.
SQL — para criar e manipular o banco de dados.

# Para o frontend (a parte que o usuário vê e usa):

HTML — estrutura das páginas.
CSS — aparência e estilo.

JavaScript — interações, como a busca de clientes e a atualização das listas.

## Banco de dados:
SQL Server, PostgreSQL ou MySQL — um desses para guardar os dados.

## Ferramentas de trabalho:

Visual Studio ou VS Code — para escrever o código.
Git — para controlar as versões do projeto.
Draw.io ou brModelo — para desenhar o DER (diagrama do banco).

## API Controllers e Rotas, Feito no Site BRMW:

<img width="822" height="599" alt="image" src="https://github.com/user-attachments/assets/90e69a01-a6aa-4a4f-967d-9dd76d5de780" />

## Linguagens e Tecnologias Necessárias:

C# — backend (API, login, criptografia dos dados).
SQL — banco de dados (criação das tabelas, consultas, registros).
HTML, CSS e JavaScript — frontend (as telas que o usuário usa).

## Banco de Dados:
SQL Server

##ferramentas:
-Visual Studios  
-VS Code
-Git
-BRMW - para fazer o modelo dos controlers

##Equipamento:
computador com acesso a Internet, teclado mouse e monitor.

## Regras de Negócios nos qual devemos seguir - Tiradas da atividade classroom:

1. Dados iniciais
O script do banco precisa ter pelo menos 3 registros em cada tabela, respeitando os tipos de dados, as chaves primárias e as chaves estrangeiras.

2. Autenticação
No login, se o usuário errar as credenciais, o sistema deve avisar que a autenticação falhou.

3. Segurança
Os dados sensíveis (como CPF e contato) devem ser criptografados no banco de dados, seguindo a LGPD.

4. Tela principal
Depois de logar, o sistema deve mostrar: o nome do usuário logado, um jeito de acessar os outros recursos e uma opção para sair do sistema.

5. Gestão de clientes
Deve ter um campo de busca: o usuário digita o termo, confirma, e a lista de clientes se atualiza mostrando só os registros que correspondem.

6. Gestão de agendamentos
Deve exibir a lista de agendamentos ordenada pelo dia, trazendo todos os dados do cliente e do veículo.

7. Associação de dados
Ao cadastrar um veículo novo, o usuário precisa associá-lo a um cliente.

   
