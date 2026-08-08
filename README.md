Here we have multiple branch

# master

# v1
- git checkout v1
- docker build -t colorapp:v1 .
- docker run --name color-app -p 8080:8080 colorapp:v1
- curl locahost:8080/info

# v2
# v3
