
# Login and Signup UI

This repository contains the **Login** and **Signup** user interface built with **React.js**. The UI includes password strength validation and the ability to toggle password visibility (show/hide) during registration and login. It's designed for sports performance monitoring and event management systems but can be adapted for other applications.

## Table of Contents
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Login Page**:
  - Email and password input fields.
  - Show/Hide password functionality.
  - Validation for required fields.
  
- **Signup Page**:
  - Username, email, password, confirm password, and role input fields.
  - Password strength meter.
  - Show/Hide password and confirm password functionality.
  - Validation for matching passwords and required fields.
  - Dropdown to select the role (Athlete, Coach, Admin).
  
- **Responsive Design**: 
  - Works well on both desktop and mobile devices.
  
## Project Structure

```
/src
│
├── components/
│   ├── Login.js
│   ├── Register.js
│   ├── PasswordStrengthMeter.js
│
├── styles/
│   ├── LoginRegister.css
│
└── App.js
```

- `Login.js`: Implements the login form with email and password fields.
- `Register.js`: Implements the registration form with username, email, password, confirm password, and role fields.
- `PasswordStrengthMeter.js`: Displays a strength meter for the password input.
- `LoginRegister.css`: Contains all styles related to the forms.

## Technologies Used
- **React.js**: Frontend library for building user interfaces.
- **CSS**: For styling the UI components.
- **React Router**: For navigation between the login and signup pages.
  
## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SportsPerformance/login-signup-ui.git
   cd login-signup-ui
   ```

2. **Install the dependencies**:
   ```bash
   npm install
   ```

3. **Run the project**:
   ```bash
   npm start
   ```

   The application should now be running at `http://localhost:3000`.

## Usage

1. **Login**: Users can enter their email and password. The password field supports the toggle functionality to show or hide the entered password.
  
2. **Register**: Users can fill out the registration form. The password strength is checked and displayed. Passwords can be shown or hidden with the toggle feature, and both passwords (password and confirm password) must match before submitting the form.

## Screenshots

### Login Page
![Login Page Screenshot](https://github.com/SportsPerformance/login-signup-ui/blob/signup-page/public/Screenshots/Login%20page.png)

### Signup Page
![Signup Page Screenshot](https://github.com/SportsPerformance/login-signup-ui/blob/signup-page/public/Screenshots/Signup%20page.png)

## Contributing

Feel free to submit issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
