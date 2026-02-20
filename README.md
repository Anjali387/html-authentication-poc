# HTML Authentication Poc

This repository contains a simple authentication flow created using **only HTML**.  
The purpose of this project is to understand basic page navigation and redirection using anchor (`<a>`) tags, without using any CSS or JavaScript.

This project is developed as part of an academic assignment and focuses purely on HTML structure.

## Pages Included

The project contains the following five HTML pages:

1. **login.html**  
   - Acts as the entry point of the application  
   - Provides links to Register, Forgot Password, and Dashboard

2. **register.html**  
   - Used for new user registration  
   - Redirects back to the Login page after registration

3. **forgot-password.html**  
   - Allows users to request a password reset  
   - Redirects to the Reset Password page

4. **reset-password.html**  
   - Used to reset the user’s password  
   - Redirects back to the Login page

5. **dashboard.html**  
   - Represents a successful login state  
   - Includes a Logout option that redirects to Login

## Navigation Flow

- Login → Dashboard  
- Login → Register → Login  
- Login → Forgot Password → Reset Password → Login  
- Dashboard → Logout → Login  

All navigation is handled **only using anchor tags**.

## Technologies Used

- HTML5  
- No CSS  
- No JavaScript  

This ensures the project remains simple and meets the assignment constraints.

## How to Run the Project

1. Clone or download this repository.
2. Open `login.html` in any web browser.
3. Use the links on each page to navigate through the authentication flow.

No additional setup is required.
## Important Notes

- This is a **front-end proof of concept only**.
- No actual authentication or validation is performed.
- The repository is **public** as required for evaluation.
- 
## Purpose of the Project

The main goal of this project is to:
- Understand basic HTML page structure
- Learn how redirection works using anchor tags
- Practice organizing multiple HTML files in a project


Thank you for reviewing this project 🙂
