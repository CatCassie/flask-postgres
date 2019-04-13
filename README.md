```
sudo docker-compose up
```
```
sudo docker exec -it 738b1f6f46be /bin/bash
```
```
psql postgres postgres
```
```
CREATE DATABASE book_store;
```
# list the databases in list
```
\l 
```
# connect to the database
```
\c books_store
```
# list tables in the database
```
\dt
```
# run app server
```
python3 manage.py runserver
```
