# Laravel 10, Reactjs and devcontainer

## Requirements
- [Visual Code](https://code.visualstudio.com/)
- [Dev container extensions](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Composer](https://getcomposer.org/)

## Developments
Clone this repository 
```bash
git clone https://github.com/zestzero/laravel-10-reactjs <PROJECT_NAME>
```
Get into `app`` folder
```bash
cd app
```
Install dependencies using composer:
```bash
composer install
```
Copy ``.env.example`` to `.env`
```bash
cp .env.example .env
```

`CTRL + Shift + P ` or `CMD + Shift + P` and select `Dev Containers: Open Workspace in Container.`

Inside your devcontainer workspace, run following commands:
```bash
php artisan key:generate
yarn install
yarn dev
```
That's it! browse your website via http://localhost

Happy hacking ❤️ 