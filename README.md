11. Add a button next to the task box title.

    1. Create "Add Task" button on the right of the task title.
    2. Add SVG icon on the left of the button text.

12. After clicking the button a popup should open.
    1. Design the UI of the popup including input field(s) and submit button in a different project.
    2. Add the popup in the specific component of our project
    3. Implement click event functionality in the "Add Task" button with the popup opening. 
    4. Check if the pop up works accordingly the button is clicked.

13. Clicking the submit button, tasks should be added and the popup should close.

    1. Impement Data binding option in the input field of the popup.
    2. Create the api calling function to add a new task.
    3. Add a click event in the submit button to execute api calling function.
    4. check in the console if the api calling function works when the submit button is clicked.
    5. show the newly added task in the first task box(IDEAS).  


14. Refactor and restructure




## Task

1. Initial ng setup.

2. Tailwind configaration.

3. Create a dashboard component.

4. Create the required UI design.

5. Implement the design in the dashboard component.

6. Create local database using json server.

   1. Install json-server.

   2. Install Concurrently.

   3. Add concurently command in script in package.json file.

   4. Create 'data' folder in root and create 'db.json' file in it.

   5. In 'db.json' file, create specific data  for the task board.

   6. Run the application with concurruntly command.

8. Call data from the api from json server.

9. Show every specific data in the related box.

10. Add drag and drop option along with specific api calling.

11. ✅Check if everything works.

# Angular Task Board Application

## Description
This Angular task board application allows users to manage tasks by organizing them into four categories: Ideas, Research, Todo, and Done. Users can transfer tasks between these categories using drag and drop functionality, updating the task status accordingly.

## Installation

To run the application locally, follow these steps:



#### 1 Clone or download the repository:
```bash
https://github.com/AmirHam-Za/ng-Task-Board
```
#### 2 Run command to install dependencies: 
```bash
npm install
```

#### 3 Start the JSON server and Angular application concurrently by running:
```bash
npm run start
```

#### 4 Navigate to this link to view the application in the browser:
```bash
http://localhost:4200
```
## Tools Used

- [Angular](https://angular.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [JSON Server](https://github.com/typicode/json-server)
- [Concurrently](https://github.com/kimmobrunfeldt/concurrently)



