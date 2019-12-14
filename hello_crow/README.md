command to execute
docker run --rm -d -v $(pwd):/usr/src/webapp/ -p 8080:8080/tcp -e PORT=8080 cppbox:latest /usr/src/webapp/build/hello_crow