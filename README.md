# django-noentry
django no entry 

## docker run
```
docker run --name docker-django -d --restart=always -p 8000:8000 -v $PWD:/app:z -t amarinboonkirt/django-noentry
```
## start django
```
docker exec -it docker-djang bash -c "cd /app; python -W "ignore" manage.py runserver 0.0.0.0:8000 --insecure;"
```
