sudo docker build -t backend-example
touch logs.txt
sudo docker run -v $(pwd)/logs.txt:/backend-example/logs.txt --rm -d -p 8000:8000 bakend-example
