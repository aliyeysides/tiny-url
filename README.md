tiny url shortener using flask and redis

```zsh
# install python dependency
pip install flask redis

# run redis from docker
docker run --name tiny-url-shortener-redis -p 6379:6379 -d redis

# start web server
FLASK_APP=. flask run
```