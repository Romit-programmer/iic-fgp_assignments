In this week's assignment i have learnt the following javascript concepts:Variables (let, const), Data Types, Operators.
Functions, Arrow Functions, Closures.
DOM Manipulation, Event Listeners.
Promises, Async/Await.
Modules and Imports.
I have gathered knowledge about these topics as instructed by my mentor ...from youtube and various other sources from the internet and using my knowledge of html and css combined with the topics that i learnt i have built a very simple yet clean task tracking webpage which of course implements all the javascript concepts mentioned above. Here are the snippets of my code where i have implemented specific concepts.
Implementation:
1)Arrow functions: const clearError = () => {
    errorMessage.textContent = '';
};

const updateStats = () => {
    const completed = tasks.filter(task => task.completed).length;
    const total = tasks.length;
    // ... function body
};

2)DOM manipulations:
// Creating elements
const li = document.createElement('li');
const checkbox = document.createElement('input');

// Modifying attributes and properties
checkbox.type = 'checkbox';
li.className = 'task-item';
li.dataset.id = task.id;

// Modifying content
span.textContent = task.text;

// Appending elements
li.appendChild(checkbox);
li.appendChild(span);
taskList.appendChild(li);

// Modifying styles
span.classList.toggle('completed');


3)Event Listeners
// Click events
document.getElementById('addTask').addEventListener('click', async () => {
    // ... event handler
});

// Keyboard events
taskInput.addEventListener('keypress', async (e) => {
    if (e.key === 'Enter') {
        // ... event handler
    }
});

// Change events
checkbox.addEventListener('change', () => {
    task.completed = checkbox.checked;
    span.classList.toggle('completed');
    updateStats();
});


4)Async/Await

// Click events
document.getElementById('addTask').addEventListener('click', async () => {
    // ... event handler
});

// Keyboard events
taskInput.addEventListener('keypress', async (e) => {
    if (e.key === 'Enter') {
        // ... event handler
    }
});

// Change events
checkbox.addEventListener('change', () => {
    task.completed = checkbox.checked;
    span.classList.toggle('completed');
    updateStats();
});