# Adonis Job Board Application

This is the web application using fullstack framework AdonisJs.

Screenshot:

![screenshot](https://github.com/zuolizhu/AdonisProjects/blob/master/jobboard/screenshots/screenshot.jpg)

## To run this project

```bash
adonis serve --dev
```



Config `.env` file to match your local environment setting

```markdown
HOST=127.0.0.1
PORT=3333
NODE_ENV=development
APP_URL=http://${HOST}:${PORT}
CACHE_VIEWS=false
APP_KEY=jBgDHpoSFVdNHuiDs9g1cWib00gdW4s0
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_USER=root
DB_PASSWORD={dbpassword}
DB_DATABASE=jobboard
SESSION_DRIVER=cookie
HASH_DRIVER=bcrypt
```

