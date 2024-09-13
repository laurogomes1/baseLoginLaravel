<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Logo do Laravel">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/laurogomes1/baseLoginLaravel" alt="Licença">
  <img src="https://img.shields.io/github/stars/laurogomes1/baseLoginLaravel" alt="Stars">
  <img src="https://img.shields.io/github/forks/laurogomes1/baseLoginLaravel" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/laurogomes1/baseLoginLaravel" alt="Último Commit">
</p>

# baseLoginLaravel

**baseLoginLaravel** é um sistema básico de autenticação desenvolvido em Laravel, criado com o objetivo de demonstrar a implementação de um sistema de login e registro de usuários. Este projeto faz parte do meu portfólio e servirá como base para outros projetos que utilizam o Laravel.

## Funcionalidades

-   **Registro de Usuários:** Permite que novos usuários se registrem com validação de dados.
-   **Login/Logout:** Autenticação de usuários com gerenciamento de sessões seguro.
-   **Recuperação de Senha:** Função para resetar a senha via e-mail.
-   **Proteção de Rotas:** Utilização de middleware para proteger rotas que requerem autenticação.
-   **Interface Responsiva:** Front-end desenvolvido com Blade templates e CSS.
-   **Boas Práticas de Segurança:** Senhas criptografadas usando bcrypt e proteção contra ataques comuns.

## Tecnologias Utilizadas

-   **Laravel 10**
-   **PHP 8.1**
-   **Composer**
-   **MySQL**

## Instalação e Configuração

1. **Clone o repositório:**

    ```bash
    git clone https://github.com/laurogomes1/baseLoginLaravel.git
    ```

2. **Adicione suas credenciais no arquivo `.env`:**

    Configure as credenciais do seu banco de dados MySQL no arquivo `.env`.

3. **Instale as dependências do Composer:**

    ```bash
    composer install
    ```

4. **Gere a chave da aplicação:**

    ```bash
    php artisan key:generate
    ```

5. **Execute as migrações:**

    ```bash
    php artisan migrate
    ```

6. **Inicie o servidor de desenvolvimento:**

    ```bash
    php artisan serve
    ```

## Contato

-   Email: [lauro.silva@1clickmkt.com.br](mailto:lauro.silva@1clickmkt.com.br)
-   LinkedIn: [Lauro Gomes](https://www.linkedin.com/in/lauro-gomes-537273b1/)

## Sobre o Projeto baseLoginLaravel

**baseLoginLaravel** é um sistema básico de autenticação desenvolvido em Laravel, criado para demonstrar a implementação de um sistema de login e registro de usuários. Este projeto faz parte do meu portfólio e serve como base para aplicações que necessitam de funcionalidades de autenticação seguras e eficientes.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
