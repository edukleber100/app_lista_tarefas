# Aplicativo Lista de Tarefas

Este é um aplicativo simples de Lista de Tarefas desenvolvido como parte de um curso de Desenvolvimento Web. O projeto utiliza PHP com PDO para interação com o banco de dados MySQL, e incorpora o framework Bootstrap para a criação de uma interface amigável e responsiva.

## Funcionalidades

- **Adição de Tarefas:** Permite adicionar novas tarefas à lista.
- **Edição de Tarefas:** Possibilidade de editar o nome de uma tarefa existente.
- **Exclusão de Tarefas:** Permite remover tarefas da lista.
- **Marcação de Tarefas Concluídas:** Permite marcar tarefas como concluídas.

## Tecnologias Utilizadas

- **PHP:** Linguagem de programação utilizada para a lógica do aplicativo.
- **PDO (PHP Data Objects):** Camada de abstração de acesso a dados em PHP, utilizada para interagir com o banco de dados MySQL.
- **MySQL:** Banco de dados relacional utilizado para armazenar as informações das tarefas.
- **Bootstrap:** Framework front-end utilizado para a criação de uma interface moderna e responsiva.
- **HTML e CSS:** Utilizados para estruturação e estilização da página web.

## Estrutura do Projeto

- **`index.php`:** Página principal que exibe todas as tarefas, permitindo a interação com as funcionalidades do aplicativo.
- **`nova_tarefa.php`:** Página que permite a adição de novas tarefas.
- **`tarefa_controller.php`:** Controlador PHP que processa as requisições, realiza a interação com o banco de dados e redireciona o usuário para as páginas apropriadas.
- **`app_lista_tarefas_private`:** Pasta contendo arquivos relacionados à lógica de negócios do aplicativo, como o modelo (`tarefa.model.php`), o serviço (`tarefa.service.php`), a conexão com o banco de dados (`conexao.php`) e o controlador (`tarefa_controller.php`).
