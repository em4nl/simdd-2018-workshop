This the source code for a website with materials for @wolfgangschoeffel's and my workshop at the Swiss Interactive Media Design Day 2018. The website is built with [eleventy](https://11ty.io/), the static pages are in the `/docs` directory so it can be hosted at github pages at https://em4nl.github.io/simdd-2018-workshop.

## How to build locally

### Downloading and installing dependencies

```sh
git clone https://github.com/em4nl/simdd-2018-workshop.git
cd simdd-2018-workshop
npm install
```

### Building the site

```sh
npm run build
```

or

```sh
npx eleventy
```

### Running a development server

Run a development server with livereloading

```sh
npm run devserver
```

or

```sh
npx eleventy --serve
```
