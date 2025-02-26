# Sistema de Autenticação Django Usando SQLite - Desafio Técnico de Login

![Django Logo](https://www.djangoproject.com/s/img/logos/django-logo-negative.png)

## Visão Geral

Este projeto Django implementa um sistema de autenticação robusto utilizando SQLite como banco de dados. Com a crescente importância da segurança na autenticação de usuários em aplicações web, este projeto fornece uma base sólida para implementação de funcionalidades como registro, login, logout e gerenciamento de senhas.

## Funcionalidades Principais

- **Registro de Usuário:** Usuários podem criar novas contas fornecendo um nome de usuário único, um e-mail válido e uma senha segura.
- **Autenticação de Usuário:** Usuários registrados podem fazer login de forma segura utilizando seu nome de usuário/e-mail e senha.
- **Gerenciamento de Sessão:** Após a autenticação bem-sucedida, o sistema estabelece uma sessão para cada usuário, permitindo a navegação em áreas autenticadas sem necessidade de reautenticação a cada requisição.
- **Gerenciamento de Senha:** Usuários podem redefinir a senha caso a esqueçam e alterá-la para aumentar a segurança da conta.

## Tecnologias Utilizadas

- **Django:** O framework web fornece uma arquitetura segura e escalável para aplicações, incluindo recursos robustos de autenticação de usuários.
- **SQLite:** Um sistema de gerenciamento de banco de dados relacional leve e autônomo, ideal para desenvolvimento e ambientes de produção de pequeno porte.
- **HTML/CSS/JavaScript:** Tecnologias frontend usadas para criar interfaces intuitivas e melhorar a experiência do usuário.

## Como instalar em minha máquina?

1. Clone este repositório para sua máquina local.
2. Instale o Django e outras dependências executando `pip install -r requirements.txt`.
3. Aplique as migrações para criar o esquema do banco de dados SQLite: `python manage.py migrate`.
4. Inicie o servidor de desenvolvimento: `python manage.py runserver`.
5. Acesse a aplicação no seu navegador através de `http://localhost:8000` ou `http://127.0.0.1:8000`.


## Informações finais

Este projeto Django foi feito para um desafio técnico de estágio na empresa "Fidelity Pesquisas Cadastrais".
