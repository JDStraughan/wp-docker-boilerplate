# Wordpress Docker Wrapper

A simple setup to develop on Wordpress locally w/ `php.ini` override for larger file uploads

## Getting Started

Install Docker. Copy this repo into your new repo. Run Docker.

### Prerequisites

You need Docker

Get Docker at [https://docs.docker.com/get-docker](https://docs.docker.com/get-docker)

### Lift Off

#### Git Submodule Method

1. Create the folder you want to build your site in
1. Open a terminal window in that folder
1. Initialize your new git repo:
    `git init`
1. Add this repo as a submodule:
    `git submodule add https://github.com/JDStraughan/wp-docker-boilerplate.git`
1. Symlink the `docker-compose.yml` file:
    `ln -s ./wp-docker-boilerplate/docker-compose.yml docker-compose.yml`
    `ln -s ./wp-docker-boilerplate/uploads.ini uploads.ini`
1. Run `docker compose up`
1. Visit `localhost:8000` in your browser
1. ???
1. Profit

#### Copy Pasta Method

1. Create the folder you want to build your site in
1. Copy these files in the folder from #1
1. cd into your new folder
1. Run `docker compose up`
1. Visit `localhost:8000` in your browser
1. ???
1. Profit

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

## Contact

Jason Straughan - [@jdstraughan](https://x.com/jdstraughan) - <jdstraughan@gmail.com>
