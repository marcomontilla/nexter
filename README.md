[![github.com/marcomontilla](https://avatars2.githubusercontent.com/u/25273655?v=4&s=120)](https://github.com/marcomontilla/)

# Nexter
This repo contains the source code for the front-end for **Nexter**, to see the live demo go [here - Nexter](https://marcomontilla.github.io/nexter/)


### Getting Started

There are two methods for getting started with this repo.

#### Familiar with Git?
Checkout this repo, install dependencies, then start with the following:

```sh
> git clone https://github.com/marcomontilla/nexter.git
> cd nexter
> yarn install
> yarn run build:css
> google-chrome index.html
```

#### Not Familiar with Git?
Then download the .zip file.  Extract the contents of the zip file, then open your terminal, change to the project directory, and:

```sh
> yarn install
> yarn run build:css
> google-chrome index.html
```

#### Scripts
* watch:sass -> Compile all SASS Code to CSS and keeps watching modifications
* devserver -> Runs on localhost:8080
* start -> Runs on localhost:8080 and keeps watching modifications
* compile:sass -> Compile all SASS Code to CSS
* prefix:css -> Adds the CSS prefixes
* compress:css -> Minify the CSS file
* build:css -> Production Build