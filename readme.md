# WordPress Editor Partial

> Partial with the default styles used from the editor in post and
> pages and other CPT.

## Installation

You can install the file with bowe easily by typing this command on your
terminal: 


# After the installation 

You only need to include the path of the sass file into your entry point
file that is compiled from sass for example: 

**style.scss**

### With NPM

```bash
npm install wp.scss --save

@import "./node_modules/wp.scss/wp";
```

### With bower

```bash
bower install wp.scss
```
```sass
@import "./bower_components/wp.scss/wp";
```
