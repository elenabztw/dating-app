# Person Viewer App (React)

A simple React application to view a list of people one by one, with the ability to navigate through them using **Previous** and **Next** buttons. This app demonstrates the use of **React hooks**, **state management**, and **dynamic rendering**.

---

## Features

* Display one person at a time from a list of data  
* Navigate to the previous or next person using buttons  
* Shows each person's **ID, name, age, description, and photo**  
* Automatically loops around the list when reaching the first or last person  

---

## Technologies

| File       | Description                                             |
|------------|---------------------------------------------------------|
| `App.js`   | Main React component with state and navigation logic   |
| `Data.js`  | Array of person objects with id, name, description, age, and image |
| `App.css`  | Styling for the app                                     |

---

##  Installation & Run

# Clone the repository
git clone https://github.com/your-username/person-viewer.git
cd person-viewer

# Install dependencies
npm install

# Run the app
npm start


**Usage**

View one person at a time on the screen.

Click Next to view the next person.

Click Previous to go back to the previous person.

The navigation wraps around automatically when reaching the end or beginning of the list.

**React Features Used**

useState Hook – to store the current person's index

Dynamic Rendering – renders person details based on the state

Event Handling – button clicks update the state

Conditional Logic – wraps around the list when reaching the first or last item

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
