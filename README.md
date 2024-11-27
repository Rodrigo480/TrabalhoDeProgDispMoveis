# TrabalhoDeProgDispMoveis
Trabalho final de Programação para Dispositivos Móveis

Link para o vídeo de apresentação: 

ToDoApp

Rodrigo Hideho Kamada Tanaka - 2020.1904.035-0

Visão Geral do Software
O ToDoApp é um aplicativo simples de gerenciamento de tarefas que permite aos usuários criar, visualizar, editar e excluir tarefas. O objetivo do app é facilitar a organização pessoal e melhorar a produtividade, oferecendo uma interface amigável e funcional para o gerenciamento de atividades.

Papéis e Usuários
O ToDoApp possui os seguintes papéis de usuário: Usuário Comum
Cadastro e Login: Pode criar uma conta no aplicativo usando um email e senha.
Pode fazer login para acessar suas tarefas.
Gerenciamento de Tarefas: Adicionar novas tarefas, incluindo título e descrição.
Marcar tarefas como concluídas ou pendentes.
Editar tarefas existentes.
Excluir tarefas que não são mais necessárias.

Requisitos Funcionais
Usuários Permitidos
O app permite o uso apenas por usuários autenticados. Cada usuário precisa se cadastrar e fazer login para gerenciar suas tarefas.
Ações Permitidas
Usuário Não Autenticado: Registrar-se fornecendo email e senha.
Fazer login para acessar o sistema.
Usuário Autenticado: Criar, editar, visualizar e excluir tarefas.
Marcar tarefas como concluídas ou pendentes.
Entradas Necessárias

Cadastro de Usuário:
Email.
Senha.
Login:
Email.
Senha.

Gerenciamento de Tarefas:
Título da tarefa.
Descrição da tarefa.
Status (Concluída/Pendente).
Processamento Realizado

Cadastro e Login:
Salvamento dos dados de usuários em um banco de dados SQLite.
Validação de credenciais de login.
Gerenciamento de Tarefas:
Salvamento de novas tarefas no banco de dados.
Atualização de tarefas existentes.
Exclusão de tarefas do banco de dados.
Relatórios e Saídas

Lista de Tarefas:
Exibe todas as tarefas cadastradas por um usuário, incluindo:
Título.
Descrição.
Status (Concluída ou Pendente).
Mensagens de Status:
Sucesso ou erro ao realizar ações, como salvar, editar ou excluir tarefas.

Tecnologias Utilizadas
Linguagem de Programação: Java.
Banco de Dados: SQLite.
Ambiente de Desenvolvimento: Android Studio.
