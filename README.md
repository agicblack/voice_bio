# Пример аутенфикации по голосу с использованием tensorflow

# установка

- Docker
-  data/scripts/files/first голосовые примеры первого человека 
-  data/scripts/files/second  второго
-  data/scripts/files/test тестовые файлы

------------
docker-compose build && docker-compose up -d

docker exec -it tensorflow /bin/bash -c "TERM=$TERM exec bash"
~~~~

/scripts folder and run
~~~~
python tf.py
~~~~

