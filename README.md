# ecommerce-pern

After cloning project you need to build postgresql container in `server` folder

```
sudo docker-compose up --build
```

And next time in server folder to start server just use

```
sudo docker-compose up
npm run dev
```

To connect to Postgresql in VSCode you may use `PostgreSQL (ckolkman)` VSCode plugin. To connect to database with this plugin use `.env` data username, password and etc.
