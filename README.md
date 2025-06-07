````markdown
# Projeto Kanban Ruby on Rails

## Descrição

Projeto desenvolvido em **Ruby on Rails** para construir uma estrutura ágil de **Kanban** com as seguintes funcionalidades:

- Criar, atualizar, deletar e mostrar tarefas;
- Mover tarefas entre diferentes status;
- Exibir um Dashboard com dados sobre as tarefas.

---

## Requerimentos

- Ruby on Rails 7.0.7.2  
- Ruby 3.2.2  
- Javascript  
- PostgreSQL 15

---

## Para Executar o Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/Alex-dev-if/Kanban_ruby_on_rails.git](https://github.com/matheushiramatsu/kanban_uninove.git
````

2. Abra o projeto no seu editor de código:

   Entre na pasta `Kanban_ruby_on_rails`.
   No VSCode, por exemplo, abra o terminal nessa pasta e execute:

   ```bash
   code .
   ```

3. Configure o banco de dados:

   * Abra o arquivo `config/database.yml`.
   * Nos campos `username` e `password`, substitua pelos seus dados do PostgreSQL.

4. Crie e configure o banco de dados:

   ```bash
   rails db:create
   rails db:migrate
   ```

5. Inicie o servidor:

   ```bash
   rails s
   ```

6. Acesse a aplicação no navegador:

   * Por padrão em: `http://localhost:3000` ou `http://127.0.0.1:3000`

> **Obs:** Caso ocorra algum erro, tente atualizar a página, isso normalmente resolve.

---

## Como Utilizar o Aplicativo

* **Criar nova tarefa:**
  Clique no botão **"nova tarefa"**, preencha nome, descrição e status, e clique em **"salvar"**.

* **Alterar status da tarefa:**
  Arraste a tarefa entre as colunas: **a fazer**, **em progresso** e **concluídas**.

* **Editar tarefa:**
  Clique em **"mostrar tarefa"** e depois em **"editar a tarefa"**.

* **Deletar tarefa:**
  Clique em **"mostrar tarefa"** e depois em **"apagar"**.

* **Dashboard:**
  Clique no botão **"dashboard"** para visualizar dados e estatísticas das tarefas.

---

## Diagrama UML

KANBAN

*(Diagrama UML representando a estrutura e os relacionamentos do sistema Kanban.)*

```

Se quiser, posso ajudar também a criar um badge, seção de contribuições ou algo mais!
```
