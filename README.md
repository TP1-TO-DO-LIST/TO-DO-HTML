# TO-DO-HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@400;700&display=swap" rel="stylesheet">
    <title>To Do List App</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://www.gstatic.com/firebasejs/8.10.0/firebase-app.js"></script>
    <script src="https://www.gstatic.com/firebasejs/8.10.0/firebase-firestore.js"></script>
    <script src="https://www.gstatic.com/firebasejs/8.10.0/firebase-analytics.js"></script>
    <script src="./firebase.js"></script>
    <script src="./script.js"></script>
</head>
<body>
    <div class="background-image">
        <img src="assets/bg-desktop-dark.jpg">
    </div>
    <div class="container">
        <div class="header">
            <div class="title">
                TODO
            </div>
            <div class="theme">
                <img src="assets/icon-sun.svg">
            </div>
        </div>
        <div class="new-todo">
            <div class="check">
                <div class="check-mark">
                </div>
            </div>
            <div class="new-todo-input">
                <form onsubmit="addItem(event)">
                    <input id="todo-input" type="text" placeholder="Create a new todo..." />
                </form>
            </div>
        </div>
        <div class="todo-items-wrapper">
            <div class="todo-items">
                <div class="todo-item">
                    <div class="check">
                        <div class="check-mark checked">
                            <img src="assets/icon-check.svg">
                        </div>
                    </div>
                    <div class="todo-text checked">
                        Cut the lawn
                    </div>
                </div>
                <div class="todo-item">
                    <div class="check">
                        <div class="check-mark">
                            
                        </div>
                    </div>
                    <div class="todo-text">
                        Cut the lawn
                    </div>
                </div>
                <div class="todo-item">
                    <div class="check">
                        <div class="check-mark">
                        </div>
                    </div>
                    <div class="todo-text">
                        Cut the lawn
                    </div>
                </div>
            </div>
            <div class="todo-items-info">
                <div class="items-left">
                    5 items left
                </div>
                <div class="items-statuses">
                    <span class="active">All</span>
                    <span>Active</span>
                    <span>Completed</span>
                </div>
                <div class="items-clear">
                    <span>Clear Completed</span>
                </div>
            </div>
        </div>
    </div>
    

    
</body>
</html>
