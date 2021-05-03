# jekyll_docker_blog
This respository shows step by step tutorial on how you can use Jekyll to create a blog

You can ignore Docker stuff if you want and use Jekyll directly.

## Usage with Docker

Building:

```
make build
```

Serving:

```
make serve
```

Then open [http://localhost:4000](http://localhost:4000).

## Usage without Docker

```bash
# clone repo 
git clone https://github.com/ssiddique-info/jekyll_docker_blog.git

# cd and install jekyll
cd jekyll_docker_blog
sudo gem install jekyll

# start
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000).