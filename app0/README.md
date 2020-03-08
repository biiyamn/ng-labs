# labs 
Angular app from scratch without ngcli
## create project structure
```
mkdir app0/src/app
touch app0/src/main.ts
touch app0/src/index.htm
touch app0/src/app/app.module.ts
touch app0/src/app/app.component.ts
```
## create package.json
```
npm init
```
## install dependencies
```
npm install @angular/core --save
npm install @angular/platform-browser --save
npm install @angular/platform-browser-dynamic --save
npm install --save-dev typescript
npm install @angular/cli --save-dev
npm install @angular/compiler-cli --save-dev
npm install --save @angular/compiler
npm install --save @angular/common
npm install --save core-js zone.js rxjs
npm install --save systemjs
```
## add scripts to package.json
```
"tsc":"tsc" 
"build": "tsc"
 npm run-script tsc -- --init
```

npm install
# add systemjs.config.js
# add es6, dom to lib in tsconfig.json
#configure experimentalDecorators

npm run build
npm i --save-dev live-server
"scripts": {
  "build": "tsc",
  "start": "live-server"
}
# https://medium.com/angular-in-depth/setting-up-angular-from-scratch-1f518c65d8ab
# https://indepth.dev/avoiding-common-confusions-with-modules-in-angular/
# https://medium.com/developing-an-angular-4-web-app/setting-up-our-angular-4-project-from-scratch-bdbc616f92f2
# https://stackoverflow.com/questions/38263406/what-are-differences-between-systemjs-and-webpack




