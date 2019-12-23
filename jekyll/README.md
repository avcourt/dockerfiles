Setting up a Ruby dev environment for Jekyll can be a bit of a pain in the ass. If you're hosting a static Jekyll site on gh-pages, you really only need a Jekyll server to view your changes, so let's just run jekyll in a container.

## Usage
- Just place the `docker-compose.yml` file in the root of your Jekyll site.
- `$ docker-compose up`
- go to `localhost:4000` in your browser to view your Jekyll site
