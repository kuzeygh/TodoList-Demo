# TodoList-Demo
TodoList Application (Spring Boot - React - Hibernate)
## Getting Started

Hey developer you don't need anything for run that application. If you have an awesome IDE like Intellij IDEA, you can just run it. If you want change something with your experience, you should look to Prerequisites :sunglasses:

Tomcat will be started on port(s): 8004 (http)

User: ismail@example.com Password: password

```
Note: Project SDK should be Java_1.8
```

### Prerequisites for build and recreate bundle.js 
Please fallow steps for build and recreate bundle.js 

```
Install npm
```

if you have node_modules folder
```
rm -rf node_modules
 ``` or ```
delete node_modules
```

if you have package-lock.json file
```
rm -rf package-lock.json
``` or ```
delete package-lock.json
```
cache verify
```
 npm cache verify
```

install dependencies
```
npm install
```

run build and webpack
```
npm start
and build project
```

## Running the tests

Run all unit tests with Intellij IDEA 


## Features are;

- Create to-do lists. Each to-do list will have a name.
- List of to-do lists.
- Delete to-do list
- Add to-do item to existing to-do list.
- Add dependency between to-do items. To-do items which have dependency can not be completed if dependent to-do item is not completed.
- Each to-do item should have a name, description, deadline, and status.
- Mark to-do item as "Complete".
- Filter to-do items (status complete or not) on a to-do list
- Order to-do items on a to-do list by deadline, name, or status.
- Delete to-do item from to-do list.

  
## H2 spring datasource
```
http://localhost:8004/h2
username: ismail
password ismail
```

<img alt="TodoList Demo" title="TodoList Demo" src="https://i.imgur.com/1X8j1RU.png" width="450">

## Screenshot
 

<img alt="TodoList Demo" title="TodoList Demo" src="https://i.imgur.com/lYSf0A4.jpg"  >

