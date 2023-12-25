## New Project
> https://nuxt.com/docs/getting-started/installation#new-project
$ podman run -it --rm -v ./:/works --workdir=/works docker.io/library/node:latest npx nuxi@latest init nuxt3-gettingstart

## Development Server
$ cd nuxt3-gettingstart
$ podman run -it --rm -p 3000:3000 -v ./:/works --workdir=/works docker.io/library/node:latest npm run dev -- -o
$ curl http://localhost:3000/
