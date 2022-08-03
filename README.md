# Angular
# Waht is Front-End (FE) framework ?
framework it's provided tools and functionalities to build my app.
- FE framework: group of functionalities provided in a single framework to bulid front-end apps using HTML, CSS, JavaScript.
- FE framework:  it's provided a way to build SPA(single page application) 
-  example: angular, react, vue.js

# Angular vs AngularJS
- AngularJS
  - ES5/ JavaScript
  - Controllers
  - No CLI(command line interface)
  - Can be combined with backend 
- Angular 
  - ES6/ JavaScript Typescript
  - Components
  - CLI(command line interface) provided
  - cannot be combined
# Angular Architecture
- Modules
- Components
- Services & DI(Dependency Injection)-design pattern
- Directives
- Pipes
- Routing
- Guards

![Architecture_of_an_Angular_2_application](https://user-images.githubusercontent.com/52491098/182458382-7c222f6f-3948-4a73-8590-8aacbf846082.png)

# Install angular 
- open cmd and write this command to check if the node installed or not ``` node -v ```
- [ Angular CLI Documentation ](https://angular.io/cli)
  - Install the CLI using the npm package manager: ``` npm install -g @angular/cli ```
  - ``` ng generate --help ```  " show all command"
  - ``` ng new my-first-project ``` "create first project"
  - ``` cd my-first-project ```
  - ``` ng serve``` / ``` ng serv -o ``` "run project"
- Know the files inside the project and what to do 

# Practical 
- Text interpolation 
Explain : In Angular, text interpolation is used to display dynamic data on the HTML template ts file and fetch data from there to the HTML template (component HTML file).
- Example: Displayed the value of a variable from TS file in HTML file 
    - in app.component.ts: Add a variable with a value

![ng-1](https://user-images.githubusercontent.com/52491098/182568434-fc5c5741-3873-4ea1-8702-ae0acb83defc.PNG)

   -- in app.component.html :

![ng-2](https://user-images.githubusercontent.com/52491098/182568501-dcba6b39-9afc-4769-aca4-d08ce4f23f72.PNG)
 
   -- in Browser : show value of title

![ng-3](https://user-images.githubusercontent.com/52491098/182569313-a7197391-371a-4f72-8d57-069129e6aad4.PNG)



