# Dockerized Laravel & Vue.js application

Complete Dockerized laravel blog app using Vue.js & mysql


<p align="center">This is the complete dockerized Laravel & Vue.js blog & forum application which can be extended to make your complete product. </p>


# About the Application

This is the only complete & powerful blog + forum application built with Laravel also having beautiful & convenient UI.

`Laravel 5.*` and `Vuejs 2.*` combined with the establishment of a good response and handy admin-panel. The admin-panel made through the `Vuejs` component development. The complete setup is workable within minutes with `docker compose 2`

## Basic Features

- Manage users, articles, discussions and media
- Statistical tables
- Categorize articles
- Label classification
- Content moderation
- Own comments system
- Multi-language switching
- Markdown Editor
- and more...

## Server Requirements

- PHP >= 7.0.0
- Node >= 6.x
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension

## Install

### 1. Clone the source code or create new project.

```shell
git clone https://github.com/granddevv/docker-laravel-vue.git
```

### 2. Set the basic config

```shell
cp .env.example .env
```

Edit the `.env` file and set the `database` and other config for the system after you copy the `.env`.example file.

### 2. Install the extended package dependency.

Install the `Laravel` extended repositories:

```shell
composer install -vvv
```

Install the `Vuejs` extended repositories:

```shel
npm install
```

Compile the js code:

```shel
npm run dev

// OR

npm run watch

// OR

npm run production
```

### 3. Run the blog install command, the command will run the `migrate` command and generate test data.

```shell
php artisan blog:install
```
