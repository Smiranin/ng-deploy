# ng-deploy-gh-pages

## What is ng-deploy-gh-pages?

 **This packege run automatic deploy of your ng-cli project on git repository in gh-pages branch**

## How to use

- npm install ng-deploy-gh-pages --save-dev
- add script in your package.json ```"deploy": "./node_modules/.bin/deploy" ```
- npm run deploy

## How does it work?

 - **Get git origin url**
 - **Build project with changed base href to the name of the repository**
 - **Create 404.html in ./dist**
 - **Init new repo in ./dist and prepare for push to gh-pages**
 - **Push files from ./dist to gh-pages**
 - **Delete ./dist**

 