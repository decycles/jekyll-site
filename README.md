# Static Site Example

This is the static site example that follows the documentation at [docs.decycl.es](https://docs.decycl.es/application-developer/examples/jekyll-site.html). Feel free to clone this template as a starting point.

In this example, the `site` folder is your web root.

This repository deploys to [jekyll-site.decycl.es](https://jekyll-site.decycl.es).

## Local Development

You can run a local development server using docker. It will be accessible at [http://0.0.0.0:4000](http://0.0.0.0:4000):

```bash
docker-compose up
```

## Build

Before committing your changes to VCS, run the build:

```bash
docker run --rm -v "${PWD}:/srv/jekyll/" jekyll/builder:4 jekyll build
```
