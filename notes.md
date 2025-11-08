## Installation

Change all the details from one place: ``_data/data.yml``

## To preview/edit locally with docker

```sh
docker-compose up
```

*docker-compose.yml* file is used to create a container that is reachable under http://localhost:4000.
Changes *_data/data.yml* will be visible after a while.

### Local machine

* Get the repo into your machine 
* Install required ruby gems
```bash
bundle install
```
* Serve the site locally
```bash
bundle exec jekyll serve --livereload
```
* Navigate to `http://localhost:4000`


