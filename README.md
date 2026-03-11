# Projeto: Gestor de Finanças Pessoais

---

Este é um projeto de estudo prático para aprender as bases do ecossistema PHP moderno, utilizando o framework Laravel e o motor de templates Blade. O objetivo é criar uma aplicação onde possamos registrar, listar e excluir despesas diárias.

---

## Tecnologias e Ferramentas

### 1. PHP (A Linguagem)

O motor principal. No Laravel, usamos o PHP moderno, que é rápido, tipado e orientado a objetos. Não se preocupe, vamos ver a sintaxe aos poucos.

### 2. Laravel (O Framework)

Ele é o "esqueleto" da aplicação. O Laravel resolve tarefas repetitivas como:

* Gerenciamento de rotas (URLs).
* Conexão com banco de dados.
* Segurança e validação de formulários.

### 3. Blade (Templates)

É a forma como o Laravel exibe o HTML. O Blade permite usar lógica (como loops e condicionais) dentro do HTML de um jeito muito mais limpo que o PHP puro.
Exemplo: Em vez de `<?php echo $nome; ?>`, usamos apenas `{{ $nome }}`.

### 4. Composer (Gerenciador de Dependências)

É o equivalente ao `npm` do Node.js ou ao `pip` do Python. Ele instala o Laravel e qualquer outra biblioteca externa que precisarmos.

### 5. Eloquent ORM

É a parte do Laravel que conversa com o banco de dados. Com ele, não precisamos escrever códigos SQL complexos. Tratamos as tabelas do banco como se fossem objetos do código.

---

## Estrutura de Pastas que vamos focar

* `routes/web.php`: Onde definimos os endereços (URLs) do site.
* `app/Http/Controllers`: Onde fica a "inteligência" (lógica) de cada página.
* `resources/views`: Onde ficam os nossos arquivos HTML/Blade.
* `database/migrations`: Onde "desenhamos" as tabelas do nosso banco de dados.
* `app/Models`: Onde definimos como os dados (Despesas) se comportam.

---

## Comandos Essenciais

Para criar o projeto:

```bash
composer create-project laravel/laravel financeiro

```

Para rodar o projeto localmente:

```bash
php artisan serve

```

Para criar um novo arquivo de lógica (Controller):

```bash
php artisan make:controller DespesaController

```

Para criar a tabela no banco de dados:

```bash
php artisan migrate

```

---

## Objetivos de Aprendizado

1. Entender o fluxo **MVC** (Model-View-Controller).
2. Criar formulários e salvar dados no banco.
3. Exibir dados do banco em uma tabela HTML.
4. Aplicar componentes Blade para não repetir código HTML.

---
