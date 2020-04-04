Angular2 is Open source client side freamword develop by Google
- Angular current version 9
- Use can develop Single Page Application(SPA) for destop or mobile
- Angular freamwork build using TypeScript lang

- Softeare required
1. Node
2. TypeScript 
3. Angular CLI
4. Editor (vs code)

How to install node.
Node is runtime which execute javascript code at server side
- it's single threaded
- We can compare node with other server side techonlogy like java, C#, C
- Node develop by Goolge
- It's also called as V8 engine (which is use by chrome browser)
Download url : https://nodejs.org/en/download/
LTS version (Long team support) means stable version
Current version (under development) not fully tested(beta version)

How to install editor VS code
- Develop by microsfot
Url : https://code.visualstudio.com/


How to verify node install ?
- open command prompt (cmd) and type 
> node
or use can check node version by 
>node --version comnad

What is npm ?
> it's just like maven repository, using npm we can download any javascript library

How to install libraray using npm
> open cmd where u need to downaload and type
npm install <libraryname> or npm i <libraryname>

ex. npm install typescript

what is angular cli >
Angular cli is like prebuild project template which is use to setup anguar project easy.
it's managed and develop by angular tool team.


How to compile typescript file.
> tsc filename.ts

How to run typescript file.
> you can not run typescript file directly. first you have to compile ts file. 
> tsc filename.ts   //ts it's source 
> node filename.js  //after compilation new file created with .js

How to run javascript file.
> node filename.js

How to setup angular project
install angular cli
>npm i @angular/cli
create project "myfirstapp"
>npm new myfirstapp
to run project - move to project folder by 
cd myfirstapp
to run
ng serve
to test project
ng test
to production release/build
ng build 
