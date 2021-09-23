cd frontend\api-service

gradle clean install

cd frontend\hello-world-service

mvn clean install "-Dmaven.test.skip=true"

then cd root-dir

docker-compose build

docker-compose up