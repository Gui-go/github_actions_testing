docker build -t flaskactions .

docker run -d -p 5000:5000 flasktry:v6

docker tag flasktry:v6 guigo-13/flasktry:v6

docker commit container_id guigo13/flasktry:v6

docker push guigo13/flasktry: