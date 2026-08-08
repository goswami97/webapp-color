Here we have multiple branch

# master
- git checkout v1
- docker build -t colorapp:latest .
- docker run --name color-app --rm --env APP_COLOR=green -p 8080:8080 colorapp:latest
- curl localhost:8080
- this version only support / 

# v1
- git checkout v1
- docker build -t colorapp:v1 .
- docker run --name color-app --rm --env APP_COLOR=green -p 8080:8080 colorapp:v1
- for i in {1..9}; do curl -s localhost:8080/info; echo; done
- this version support /, /version, /color, /info

# v2
-  everything is same just the version will be v2
  
# v3
-  everything is same just the version will be v3

Colors 
- "red",
- "green",
- "blue",
- "blue2",
- "pink",
- "darkblue"
