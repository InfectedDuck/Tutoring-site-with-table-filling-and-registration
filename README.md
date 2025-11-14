# Tutoring Site with Table Filling and Registration

## Overview

**Repee** is a comprehensive and user-friendly tutoring platform designed to enhance the educational experience for students. The platform offers a range of subjects and features experienced tutors who provide personalized, flexible learning schedules tailored to individual needs. This documentation outlines the core features and functionalities of the Repee tutoring website, including user registration, login capabilities, and administrative controls.

## Features

### 1. Home Page (`main.html`)

The primary page of the Repee website provides detailed information about the tutoring services offered. This includes:
- **Tutor Information**: Profiles and qualifications of available tutors.
- **Subject Information**: A list of subjects covered and detailed descriptions.
- **Additional Features**: Insights into tutoring methodology, scheduling flexibility, and learning outcomes.

### 2. Registration and Login Page

The registration and login functionalities are managed via a dedicated page. Key features include:
- **User Registration**: Allows new users to create an account by providing a name, email, and password. Includes password confirmation for accuracy.
- **User Login**: Existing users can log in using their credentials to access the platform.
- **Admin Login**: Special login credentials (`Username: 123admin`, `Password: 123admin123321`) are provided for administrators. This access level includes the capability to view all user data.

### 3. Data Management

- **User Data Table**: After logging in as an admin, users can view a table listing all registered users. This table displays:
  - User Name
  - User Email
  - Masked Password (for privacy)
  - Action Buttons (Edit and Delete)

### 4. Admin Functions

- **Edit User Data**: Admins can modify user information directly from the table.
- **Delete User Data**: Admins can remove user entries from the database.

### 5. Styling and Design

The website is styled using advanced CSS techniques to ensure a visually appealing and user-friendly interface:
- **Responsive Design**: The layout adapts to various screen sizes and devices.
- **Modern Aesthetics**: Includes modern design elements such as buttons with hover effects, rounded corners, and shadowing.
- **Center Alignment**: Key elements, including the toggle button and forms, are centrally aligned for a clean and organized appearance.

## Technical Details

### File Structure

1. **`main.html`**: The main document providing information about tutors and subjects.
2. **`registration.html`**: Contains both login and registration forms, as well as JavaScript functionality for form handling.
3. **`styles.css`**: The stylesheet for the entire site, including advanced styling for forms, buttons, and layout.

### JavaScript Functionality

- **Form Handling**: JavaScript is used to handle form submissions, manage user data, and control visibility of different sections based on login status.
- **Admin Controls**: Special JavaScript logic is implemented to ensure only users with admin credentials can view and manage the data table.

## License

This project is licensed under the MIT License.  
You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of this software, subject to the terms of the MIT License.  

For full details, see the [LICENSE](LICENSE) file.

