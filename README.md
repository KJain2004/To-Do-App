# React To-Do App
A simple and responsive to-do application built with React. This app allows users to add, delete, and mark tasks as complete. 
It uses localStorage to persist tasks across browser sessions.

**Features**
1. Add Tasks: Users can add tasks by typing in the input field and pressing the "ADD +" button or the Enter key.
2. Delete Tasks: Each task has a delete button to remove it from the list.
3. Mark Tasks as Complete: Users can toggle the completion status of a task by clicking on it.
4. Persistent Storage: Tasks are saved in localStorage, so they persist even after refreshing the page.
5. Responsive Design: The app is fully responsive and works seamlessly on mobile, tablet, and desktop devices.

**Technologies Used**
1. React: A JavaScript library for building user interfaces.
2. Tailwind CSS: A utility-first CSS framework for styling.
3. localStorage: Used to save tasks locally in the browser.

**Screenshots**


Screenshot 2
Mark tasks as complete or delete them.

How to Run the App Locally?
Follow these steps to set up and run the app on your local machine.

**Prerequisites**
Node.js: Make sure you have Node.js installed. You can download it from here.
npm: npm is included with Node.js.

**Installation**
Clone the Repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

**Install Dependencies:**
Run the following command to install the required dependencies:
npm install

**Run the app locally using:**
npm start
The app will open in your default browser at http://localhost:3000.

**Code Overview
Todo.jsx**
->Manages the state of the to-do list using useState.
->Handles adding, deleting, and toggling tasks.
->Persists tasks in localStorage using useEffect.

**TodoItems.jsx**
Displays individual to-do items.
Allows users to mark tasks as complete or delete them.

**Live Demo**
You can access the live version of the app here:
