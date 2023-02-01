# webapp-color

git clone https://github.com/goswami97/webapp-color.git

cd webapp-color

docker build -t local/color-app:latest .

docker run --rm -e APP_COLOR=green -p 8181:8080 local/color-app:latest


# Available colors
- red
- green
- blue
- blue2
- pink
- darkblue
