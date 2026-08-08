Here we have multiple branch

# master

# v1
- git checkout v1
- docker build -t colorapp:v1 .
- docker run --name color-app --rm --env APP_COLOR=green -p 8080:8080 colorapp:v1
- for i in {1..9}; do curl -s localhost:8080/info; echo; done

# v2
# v3
