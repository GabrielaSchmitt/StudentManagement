<h1 align="center">
  <br>Sistema de Gestão de Alunos</h1>

<div align="center">
  
![systemcompletegifers](https://github.com/GabrielaSchmitt/StudentManagement/assets/86369677/33aa178f-2191-4a9a-b21b-3d0c7d89e02a)

</div>

<a id="pt-readme"></a>
## [English](#en-readme) | Português

**Student Management** é um sistema baseado em Django e Python projetado para gerenciar informações de estudantes em uma instituição educacional fictícia. Ele utiliza o SQLite como banco de dados e oferece recursos para armazenar, adicionar, atualizar e excluir dados de estudantes, incluindo:

- Número de Estudante
- Nome
- Sobrenome
- E-mail
- Área de Estudo
- Média

O GIF animado mostra a aplicação em funcionamento, acessível através da porta 127.0.0.1:8000 .

## Como rodar os códigos

Para rodar os códigos é necessária uma IDE Python como o **VSCODE**, **Pycharm** baixe o projeto e siga alguns comandos no terminal para ver a magia acontecendo!

<br>

## Comandos

### Configurando um Ambiente Virtual
Para criar e ativar um ambiente virtual, utilize os seguintes comandos Bash:

```bash
$ python -m venv venv 
$ source venv/bin/activate
```

Instale o Django executando o seguinte comando:

```bash
$ pip install django
```

Em seguida, inicialize o seu projeto Django:

```bash
$ django-admin startproject django_project .
```

Executando o Servidor:

```bash
$ python manage.py runserver 
```

Acesse a sua aplicação através do link fornecido.

### Criando um Aplicativo Django
Crie um novo aplicativo chamado "students" com o seguinte comando:

```bash
$ python manage.py startapp students
```

Não se esqueça de adicionar este aplicativo ao arquivo `django_project/settings.py` na seção "INSTALLED_APPS".

### Gerenciando Modelos de Banco de Dados
Depois de definir os modelos de dados, gere as migrações com o seguinte comando:

```bash
$ python manage.py makemigrations
```

Se as migrações foram criadas com sucesso, aplique-as ao banco de dados:

```bash
$ python manage.py migrate 
```

### Tarefas Administrativas
Para tarefas administrativas, utilize o painel de administração do Django. Para criar uma conta de superusuário, execute:

```bash
$ python manage.py createsuperuser
```

Agora, o seu sistema de gerenciamento de estudantes está configurado e pronto para uso. Personalize-o de acordo com as suas necessidades específicas.

<br>

✨ Obrigada pela atenção! ✨


-------
<br>
<br>

<h1 align="center">
  <br>Student Management System</h1>
<a id="en-readme"></a>

## English | [Português](#pt-readme)


**Student Management** is a Django and Python-based system designed to manage student information for a fictional educational institution. It utilizes SQLite as its database and offers features for storing, adding, updating, and deleting student data, including:

- Student number
- First name
- Last name
- E-mail
- Field of study
- GPA

The animated gif shows the application running on port 127.0.0.1:8000 port.

## How to run the codes

To run the codes you need a Python IDE such as **VSCODE, Pycharm**   just download the entire project and follow the above bash commands to see magic happening! 

<br>

## Getting Started

### Setting Up a Virtual Environment
To create and activate a virtual environment, use the following Bash commands:

```bash
$ python -m venv venv 
$ source venv/bin/activate
```

Install Django by running the following command:

```bash
$ pip install django
```

Next, initialize your Django project:

```bash
$ django-admin startproject django_project .
```

Running the Server:

```bash
$ python manage.py runserver 
```

Access your application through the provided link.


Creating a Django App
Create a new app named "students" with the following command:

```bash
$ python manage.py startapp students
```

Don't forget to add this app to your django_project/settings.py file under the "INSTALLED_APPS" section.

Managing Database Models
Once you have defined your data models, generate migrations with:

```bash
$ python manage.py makemigrations
```

If the migrations were created successfully, apply them to the database:

```bash
$ python manage.py migrate
```

Administrative Tasks
For administrative tasks, use the Django admin panel. To create a superuser account, run:

```bash
$ python manage.py createsuperuser
```

Now, your student management system is set up and ready for use. Customize it according to your specific needs.

<br>

✨ Thanks for your attention! ✨
