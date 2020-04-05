#### What is Angular
 Angular/Angular2 is Open source client side freamwork develop by Google
- Angular current is version 9
- Use for develop Single Page Application(SPA) for destop or mobile
- Angular freamwork build using TypeScript lang

Software required 
- Node
- Editor(VSCode)

library required 
- TypeScript 
- Angular CLI

#### What is NodeJs
Node is runtime which execute javascript code at server side,
 it's single threaded
- We can compare node with other server side techonlogy like java, C#, C
- Node develop by Goolge
- It's also called as V8 engine (which is use by chrome browser)

#### How to install node
Download url : https://nodejs.org/en/download/
- LTS version (Long team support) means stable version
- Current version (under development) not fully tested(beta version)

#### How to install editor VS code
- Downlad Url : https://code.visualstudio.com/


#### How to verify node install ?
Open doc command Window+R / cmd 

&gt;node --version


#### What is npm ?
it's just like maven repository, using npm we can download any javascript library/package. 
it auto come with node (not need to install separately)
https://www.npmjs.com/

#### How to install libraray using npm
- Open doc command Window+R / cmd 
- &gt; npm install &lt;libraryname&gt; or npm i &lt;libraryname&gt;
| ex. npm install typescript

#### What is angular cli
Angular cli(command line interface) is like prebuild project template which is use to setup anguar project easly.
it's managed and develop by angular tool team.

installtion step https://cli.angular.io/

#### How to install typescript file.
&gt; npm install -g typescript

#### How to compile typescript file.
&gt; tsc filename.ts

#### How to run typescript file.
you can not run typescript file directly. first you have to compile ts first file. 

&gt; tsc filename.ts   //its it's compile .ts and generate .js file 

&gt; node filename.js  //it's run js 


#### How to run javascript file.
> node filename.js

#### How to create angular project

install angular cli

&gt;npm i @angular/cli

create project "myfirstapp"

&gt;ng new myfirstapp

run project 

&gt;cd myfirstapp

&gt;ng serve

to test project

&gt;ng test

to production release/build

&gt;ng build 


#### How to create page/component in angular
&gt;ng g component pagename

&gt;ng g c pagename

#### How to create service in angular
&gt;ng g service servicename

&gt;ng g s servicename

#### How to create pipe in angular
&gt;ng g pipe pipename

&gt;ng g p pipename

