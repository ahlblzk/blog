

## Basic Features

- Manage users, articles, discussions and media
- Statistical tables
- Categorize articles
- Label classification
- Content moderation
- Own comments system
- Multi-language switching
- Markdown Editor
- Roles & Permissions
- and more...

[PJ Blog](https://github.com/jcc/blog) Laravel 5.*

## Server Requirements

- PHP >= 7.1.0
- Node >= 6.x
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension

## Preview

![New Blog](https://pig-storage.b0.upaiyun.com/cover/2018/09/07/d2T4cAjTagf5L1rXH1FjLsFkJVffsPIGPkHEl2A5.jpg)

![New Blog](https://pig-storage.b0.upaiyun.com/cover/2018/09/07/4b7ExtB6NHZVh8n5KnW2673Ej6gwtLm1SUAubtpa.jpg)

## Install/安装

### 1. Clone the source code or create new project.

```shell
git clone https://github.com/jcc/blog.git
```

OR

```shell
composer create-project jcc/blog
```

### 2. Set the basic config/设置基本配置

```shell
cp .env.example .env
```

Edit the `.env` file and set the `database` and other config for the system after you copy the `.env`.example file.

### 2. Install the extended package dependency./下载laravel框架包和Vue扩展包

Install the `Laravel` extended repositories: 

```shell
composer install -vvv
```

Install the `Vuejs` extended repositories: 

```shel
npm install
```

Compile the js code: /编译js代码

```shel
npm run dev

// OR

npm run watch

// OR

npm run production
```

### 3. Run the blog install command, the command will run the `migrate` command and generate test data./执行blog的安装命令

```shell
php artisan blog:install
```

