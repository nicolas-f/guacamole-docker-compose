# Quacamole Docker compose

Create a .env file in the same folder with the following content:

```
POSTGRES_PASSWORD=EDITME_DATABASE_PASSWORD
```

Run the docker with this command

```bash
docker compose up -d
```

The open the web page http://localhost:8080/guacamole/

The default login password is *guacadmin* *guacadmin*

Change your administrator password here (it is stored in the postgresql database)

http://localhost:8080/guacamole/#/settings/preferences



