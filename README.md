# User Login and API Fetch Project

## 📌 Project Overview
This project includes a **user login page** with validation and **fetching user data from an API**. The goal is to validate user inputs and display a list of users retrieved from an external API.

## 🚀 Features
- **User Login Page:**
  - Validates email and password input fields.
  - Displays error messages for incorrect input.
  - Allows login only when credentials meet the required conditions.
- **Fetch Users from API:**
  - Retrieves user data from an external API.
  - Displays user information dynamically on the page.
  - Allows filtering users using JavaScript array methods like `.filter()` and `.map()`.

## 🛠️ Technologies Used
- **HTML** – Structure of the web page
- **CSS** – Styling for UI components
- **JavaScript** – Logic for validation and API calls
- **Fetch API** – To retrieve data from an external source

## 🔧 How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/AbdallahLearn/UserAPI.git
   ```
2. Navigate to the project directory:
   ```sh
   cd UserAPI
   ```
3. Open the `index.html` file in a browser.

## 📥 API Details
The project fetches users from:
```sh
https://jsonplaceholder.typicode.com/users
```

## 📌 Login Validation Logic
- The **email** must be a valid format (e.g., `user@example.com`).
- The **password** must be at least **6 characters long**.
- Error messages will be displayed if inputs are invalid.

## 📌 User Fetching and Display
- The fetched users are displayed inside a `<div class="container" id="userContainer"></div>`.
- Data includes **name, email, phone, address, and company**.
- Uses `.map()` and `.filter()` methods for dynamic rendering.

## 💡 Future Improvements
- Implement local authentication instead of mock validation.
- Improve UI with better styling and responsiveness.
- Add search and sorting features for users.

---

📌 **Author:** Abdullah Al-Juhani  
📌 **GitHub:** [AbdallahLearn](https://github.com/AbdallahLearn)  
📌 **License:** MIT

