- 👋 Hi, I’m @iitamit
-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>ToDo List</title>
</head>
<body>
    <div class="container">
        <h1>My To-Do List</h1>
        <input type="text" id="taskInput" placeholder="Add a new task">
        <button onclick="addTask()">Add Task</button>
        <ul id="taskList"></ul>
    </div>
    <script src="script.js"></script>
</body>
</html>body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    background-color: #fff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1 {
    text-align: center;
    color: #333;
}

input {
    width: 70%;
    padding: 8px;
    margin-right: 5px;
}

button {
    padding: 8px;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    border-bottom: 1px solid #ddd;
    padding: 10px;
    display: flex;
    justify-content: space-between;
}

li:last-child {
    border-bottom: none;
}function addTask() {
    const taskInput = document.getElementById("taskInput");
    const taskList = document.getElementById("taskList");

    if (taskInput.value.trim() !== "") {
        const li = document.createElement("li");
        li.innerHTML = ${taskInput.value} <button onclick="removeTask(this)">Remove</button>;
        taskList.appendChild(li);
        taskInput.value = "";
    }
}

function removeTask(button) {
    const taskList = document.getElementById("taskList");
    const li = button.parentNode;
    taskList.removeChild(li);
} 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
iitamit/iitamit is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
