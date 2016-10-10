<img align="right" src="img/cphbusinessWhite.png" />  
#Angular week1

##Content for the week
1. Day1: AngularJS - Intro
2. Day2: 
  - Angular Controllers, 
  - Angular Services, 
  - Angular Routing
3. Day3: Promises in Angular  
  - The $http service (connecting to a backend)  

###Topics we will cover:
- Directives
- Filters
- Two way Data binding {{}} and ng-model=""
- Views: The HTML
- Model: Javascript variables and collections
- Controllers
- Scope
- Modules
- Routes
- Factories
- Services
- Dependency Injection

## Day1 Introduction to Angular
###Study material
Recommended reading: "Angular JS Up and running" chapter 1-10.  
[Do these exercises in codeschool](https://www.codeschool.com/courses/shaping-up-with-angular-js)  
[w3school tutorial](http://www.w3schools.com/angular/angular_intro.asp)   



###What is angular  
- javascript framework
- Teaching HTML new tricks  
`<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script>`  
- ng-app
- ng-controller
- ng-model
- angular1 vs angular2
- 2 way data binding
 
###Modules
Modules:
are loaded with the ng-app directive. 
- data-ng-app("moduleName") looks for a previously loaded module


###Controllers:
- is the place where most of the work is done in Angular
- are almost always linked to a view - if it is not linked to UI it should instead be a 'service'
- is the gateway between model and view.

###Lets demo
<img align="right" src="img/demoman.png" />  
The first angular project.
<br><br><br><br><br><br><br><br><br><br>

### databinding
- dobbelt curly `{{some model variable here}}`
- `<div>{{ctrl.car.name}} is my car!</div>`
- `<div ng-bind="ctrl.car.name + ' is my car!'"></div>`

### looping
- `<div data-ng-repeat="note in notectrl.notes">`
- `<div data-ng-repeat='(author, note) in oList.notes'>`

### 2-way data binding  
```
	<html>
	<body ng-app>
	<input type="text" ng-model="name" placeholder="Enter your name">
	<h1>Hello <span ng-bind="name"></span></h1>
	<script
	src="https://ajax.googleapis.com/ajax/libs/angularjs/1.2.19/angular.js">
	</script>
	</body>
```
### Daily exercise:
[Find it here](https://github.com/CphBusCosSem3/Exercises/blob/master/SP/SP6/ExercisesAgularDay1.pdf)
## Day 2: 