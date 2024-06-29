# eshwar-demo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>To-Do List</title>
  <style>
    body
    {
    font-family: sans-serif;
    }  

h1 {
  text-align: center;
  margin-bottom: 20px;
}

#todo-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

#todo-list li {
  margin-bottom: 10px;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

#add-task-form {
  display: flex;
  justify-content: center;
  margin-top: 20px;
}

#new-task {
  flex-grow: 1;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  padding: 10px 20px;
  background-color: #4CAF50;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #3e8e41;
}
</style>
</head>
<body>
  <h1>My To-Do List</h1>
  <ul id="todo-list">
    <li>Buy groceries</li>
    <li>Finish coding project</li>
  </ul>
  <form id="add-task-form">
    <input type="text" id="new-task" placeholder="Enter new task">
    <button type="submit">Add Task</button>
  </form>
  <script src="script.js"></script>  </body>
</html>
