Descrição
Projeto desenvolvido em Ruby on Rails para construir uma estrutura ágil de Kanban com as seguintes funcionalidades:

Criar, atualizar, deletar e mostrar tarefas;

Mover tarefas entre diferentes status;

Exibir um Dashboard com dados sobre as tarefas.

Deploy:
Kanban Ruby on Rails

Requerimentos
Ruby on Rails: 7.0.7.2

Ruby: 3.2.2

Javascript

PostgreSQL: 15

Para Executar o Projeto
Clone o Repositório

No terminal, execute:

bash
Copiar
Editar
git clone https://github.com/matheushiramatsu/kanban_uninove.git
Abra o Projeto no Editor

Entre na pasta Kanban_ruby_on_rails que foi criada.
No VSCode, por exemplo, abra o terminal nessa pasta e digite:

bash
Copiar
Editar
code .
Configure o Banco de Dados

Acesse a pasta config e abra o arquivo database.yml.

Nos campos username e password, altere para seu nome de usuário e senha do PostgreSQL.

Crie e Configure o Banco de Dados

No terminal, estando na pasta Kanban_ruby_on_rails, execute:

bash
Copiar
Editar
rails db:create
rails db:migrate
Inicie o Servidor

Execute:

bash
Copiar
Editar
rails s
Acesse a Aplicação

No navegador, abra o host definido (por padrão, localhost:3000 ou 127.0.0.1:3000).

Observação: Caso ocorra algum erro, tente atualizar a página. A reinicialização da conexão pode resolver a maioria dos problemas.

Como Utilizar o Aplicativo
Criar uma nova tarefa:

Clique no botão "nova tarefa".

Preencha o nome, a descrição e selecione um status para a tarefa.

Clique em "salvar".

Mudar o Status da Tarefa:

Arraste a tarefa entre as colunas disponíveis: a fazer, em progresso e concluídas.

Editar uma Tarefa:

Clique no botão "mostrar tarefa".

Em seguida, clique no botão "editar a tarefa".

Deletar uma Tarefa:

Clique no botão "mostrar tarefa".

Em seguida, clique no botão "apagar".

Acessar o Dashboard:

Clique no botão "dashboard" para visualizar os dados e estatísticas das tarefas.

Diagrama UML
KANBAN
