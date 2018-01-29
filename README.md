# Framework7 Vue Template

A simple Framework7 Vue setup in a single HTML file

This template is targeted at beginners who want to start exploring Framework7 & Vue without the distraction of a complicated development environment.

For advanced features such as asset compilation, hot-reload and CSS extraction, we recommend that more experienced developers use [Framework7 Vue Webpack Template](https://github.com/framework7io/framework7-template-vue-webpack)

## Usage

### 1. Download this repository
```
git clone https://github.com/framework7io/framework7-template-vue-simple my-app
```

Repository will be downloaded into `my-app/` folder

### 2. Instal dependencies

Go to the downloaded repository folder and run:
```
npm install
```

This will download latest version of Framework7, Framework7-Vue, Vue (to `/www/libs/`) and required icon fonts (to `/www/fonts/`)

### 3. Run the app

```
npm run serve
```

App will be opened in browser at `http://localhost:8080/`

## Use with cordova

Just put the contents of `www` folder in your cordova's project root `www` folder

## One command install

```
git clone https://github.com/framework7io/framework7-template-vue-simple my-app &&
cd my-app &&
npm install &&
npm run serve
```

## Live Preview

https://framework7io.github.io/framework7-template-vue-simple/

