The goal of this enhancement project is to understand the existing Simple Todos code, and add the given functionalities within the existing Simple Todos code.

Your existing Simple Todos app, which you have developed, allows users to view a list of todos, and enables them to delete a todo.


### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

### Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must have the following functionalities

- Initially, the list of given todos should be displayed with a delete button for each todo
- When **Delete** button of a todo is clicked, then the respective todo should be deleted
- The `SimpleTodos` will consist of the `initialTodosList`. It consists of a list of todo objects with the following properties in each todo object

  |  Key  | Data Type |
  | :---: | :-------: |
  |  id   |  Number   |
  | title |  String   |

</details>

<details>
<summary>Enhancement Functionalities</summary>

<br/>
Functionality to be added:

To add new todos, include a text input field and an Add button at the top of the todo list.
To edit the title of a todo, place an Edit button next to each todo item. This button changes to a Save button when clicked.
To save the updated title, click the Save button, which will then changes back to an Edit button.
To mark tasks as complete, add a checkbox at the beginning of each todo item. This checkbox, when checked, strikes out the corresponding todo item.
Implement a functionality to add multiple todos with the same title at once, by entering the title and number of todos, separated by a space, in the input field.
Ensure your application maintains good CSS styling.
<br/>

</details>


