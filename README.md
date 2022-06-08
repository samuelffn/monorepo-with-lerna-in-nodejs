# monorepo-with-lerna-in-nodejs  
Projeto Monorepo utilizando o Lerna no NodeJS.  

## Criando o projeto com Yarn
mkdir monorepo-with-lerna-in-nodejs  
cd monorepo-with-lerna-in-nodejs  
git init  
yarn init -y  
mkdir packages  

## Módulo do client Express
cd packages  
mkdir clients  
mkdir express  
cd clients/express  
yarn init -y  
yarn add express  
yarn add cors  
yarn add nodemon -D
yarn add @types/express -D  
***Referências***  
**Express:** https://www.npmjs.com/package/express  
**Cors:** https://www.npmjs.com/package/cors e https://www.section.io/engineering-education/how-to-use-cors-in-nodejs-with-express/  
**Nodemon:** https://www.npmjs.com/package/nodemon  




