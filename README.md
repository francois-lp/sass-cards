# Cards with Sass
*POC to use Sass and SassDoc*

## Stack
* [Sass](https://github.com/sass/sass) - CSS processor
* [SassDoc](http://sassdoc.com/) - Comment based documentation of .scss files
* [7-1 Sass Architecture](https://www.learnhowtoprogram.com/user-interfaces/building-layouts-preprocessors/7-1-sass-architecture) - Structure of Sass projects
* [BEM methodology](https://andrew-barnes.medium.com/bem-and-sass-a-perfect-match-5e48d9bc3894) - CSS naming convention

## Requirements
* Yarn (>= 1.22.15)
* NodeJS (>= v14.18.0)

## Setup
```shell
    # clone the repo
    $ git clone https://github.com/francois-lp/sass-cards

    # install dependencies
    $ yarn global add sass
    $ yarn global add sassdoc

    # generate CSS
    $ sass --style compressed ./scss/style.scss:./public/css/style.min.css

    # generate Sass documentation
    $ sassdoc scss/
```

## Getting started
```shell
    # app
    public/index.html

    # sassdoc
    sassdoc/index.html
```

## Links
* [Sass installation](https://openclassrooms.com/fr/courses/6106181-simplifiez-vous-le-css-avec-sass/6599386-installez-sass-sur-votre-machine)
