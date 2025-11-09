Secure Auth Demo Application

This is a simple, single-page web application demonstrating user authentication using Firebase Authentication. It provides a clean, responsive interface for user registration, login, and logout functionalities.

🌟 Features

User Registration (Sign Up): Allows new users to create an account using an email and password.

User Login (Log In): Authenticates existing users to grant access to the secured view.

User Logout (Sign Out): Safely signs the user out, reverting to the authentication form.

Real-time Status: Displays the current authentication status and user ID when logged in.

Responsive Design: Styled using Tailwind CSS for excellent performance on mobile and desktop devices.

Error Handling: Provides clear messages for authentication failures (e.g., wrong password, user not found).

🛠️ Technology Stack

This application is built as a single, self-contained file, relying on the browser and the provided execution environment:

Frontend: Pure HTML5 and JavaScript (ES Modules).

Styling: Tailwind CSS (loaded via CDN) for utility-first, responsive styling.

Authentication & Persistence: Google Firebase Authentication and the Firestore SDK (for initialization) ensure secure user management and state persistence within the environment.

🚀 How to Use

Since this is a single HTML file running in a specialized environment, setup is minimal:

Open the File: Ensure the index.html file is open in the editor/preview pane.

Initial State: The app starts in the Log In mode, automatically attempting an anonymous sign-in in the background to initialize the session.

Sign Up: Click the "Need an account? Sign Up" button.

Enter a valid email address.

Enter a password (must be at least 6 characters long).

Click Sign Up.

Log In: If you created an account or are logging in later:

Enter your registered email and password.

Click Log In.

Logged In View: Upon successful login, the view switches to display a welcome message and your unique User ID.

Log Out: Click the Log Out button to securely end the session.
