# Login Form – React

A simple React login form demonstrating the use of **React State (`useState`)** to manage username, password, and login messages.

## 🚀 Live Demo

**[View Live Demo](https://muthukoornandini.github.io/student-login-react/)**

## 📂 GitHub Repository

**[View Source Code](https://github.com/muthukoornandini/student-login-react)**

## 🎯 Objective

To create a login form using React State for managing:

* Username
* Password
* Login status message

The application displays a success message when both fields contain values and displays a validation message when either field is empty.

## 🛠️ Technologies Used

* React
* JavaScript
* Vite
* HTML
* CSS
* React `useState`
* Git & GitHub
* GitHub Pages

## ✨ Features

* Username input field
* Password input field
* Login button
* State-based input handling
* Login validation
* Displays **"Login Successful"** when both fields are entered
* Displays **"Please enter username and password"** when fields are empty

## ⚛️ React State

The application uses `useState` to store the username, password, and message.

```jsx
const [username, setUsername] = useState("");
const [password, setPassword] = useState("");
const [message, setMessage] = useState("");
```

When the user enters a username:

```jsx
onChange={(e) => setUsername(e.target.value)}
```

When the user enters a password:

```jsx
onChange={(e) => setPassword(e.target.value)}
```

## 🔐 Login Validation

The login button checks whether both username and password have been entered.

```jsx
const handleLogin = () => {
  if (username && password) {
    setMessage("Login Successful");
  } else {
    setMessage("Please enter username and p
```
