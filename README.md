## 🚀 30-Day Coding Challenge: Day 27

This project is the twenty-seventh entry in my 30-day coding challenge. Today's goal was to recreate the iconic GitHub contributions graph, a fantastic exercise in data visualization, date manipulation, and handling complex grid layouts within a React application.

### 📖 Project Overview

This is a responsive clone of the GitHub user contributions graph. The application dynamically generates a grid representing the last 365 days and colors each cell based on a mock data set of "contributions." Hovering over any cell reveals a tooltip with the specific contribution count and date. The project demonstrates how to handle date logic to correctly align the calendar grid and how to manage UI state for interactive elements like tooltips.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Screenshot 2025-07-04 at 18 35 46](https://github.com/user-attachments/assets/43c2c092-b628-42e7-9fe4-423c544c401d)


### 🌟 Key Features

* **Dynamic Grid Generation:** The application automatically generates a 7x53 grid representing the last 365 days from the current date.
* **Data Visualization:** Contribution counts are visually represented by different shades of green, providing an at-a-glance overview of activity.
* **Interactive Tooltips:** Hovering over a cell displays a tooltip with the exact contribution count and the full date.
* **Accurate Date Alignment:** The grid correctly aligns the start date with the corresponding day of the week by adding empty placeholder cells.
* **Mock Data:** Uses a helper function to generate a realistic, randomized set of contribution data for demonstration purposes.
* **Custom Grid Layout:** Extends Tailwind CSS to support the complex 53-column grid required for the year-long view.

### 💻 Technologies Used

This project was built using a modern, lightweight React setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **React:** The core library for building the user interface and managing state.
* **ReactDOM:** Used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Tailwind CSS:** For all styling and for the custom grid layout.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/react-contributions-graph.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd react-contributions-graph
    ```
3.  **Open the `index.html` file in your web browser.** The CDN links will handle loading all necessary libraries automatically.

### 🎯 Learning Objectives

This project was a practical exercise in several important front-end concepts:

* **Data Visualization with React:** Learning to represent a dataset visually using conditional styling and component mapping.
* **JavaScript Date Manipulation:** Gaining experience with the `Date` object to calculate past dates and determine the day of the week.
* **Complex UI Logic:** Writing the logic to dynamically generate and correctly align a large, complex grid structure.
* **Managing Hover State and Tooltips:** Implementing a common UI pattern where hovering over an element reveals additional information.
* **Customizing CSS Frameworks:** Extending Tailwind CSS with a custom configuration to meet specific layout requirements.
