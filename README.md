```
docker-compose build
docker-compose up
docker-compose run app rake db:create
docker-compose run app rake db:migrate
```
visit http://localhost:3000