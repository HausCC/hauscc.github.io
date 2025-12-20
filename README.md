# Haus CC Website

Steps for new post

1. Add Markdown (.md) or HTML file in `_posts` or `_pages`
2. Add entry to `index.md`
3. Possibly verify with local docker
  * TBD command here


## Docker

* From https://www.inthebacklog.com/Setup-Jekyll-minimal-mistakes-docker/

```
docker build -f Dockerfile_initial -t blog .
docker run --volume="$PWD:/srv/jekyll" -it blog bundle install
docker build -t minimal-mistakes .
docker-compose up
```
