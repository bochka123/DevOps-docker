npm init
Ініціювання node.js app

docker build -t bochka123/dev:1.0 .   
Створення image докера

docker run -p 80:80 -m 100m --cpus="1" sha256:840ef89c109759da229e37ef35e3a4b0a34ae4cfe9e6d285554600ac210eb9a8 
Запуск контейнера з портом 80, обмежннням пам'яті 100мб та виділеним 1 ядром
