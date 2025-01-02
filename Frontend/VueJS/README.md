## Vuejs Training Program
Welcome to the Vue.js section of our Intern Training Program! This program is designed to introduce you to the fundamentals of Vue.js along with modern JavaScript (ES6+). You'll learn through video tutorials, hands-on coding exercises, and practical projects to help solidify your understanding of Vue.js.

### Getting Started
1. Setup Node.js Development Environment https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-22-04
2. Install Vue CLI: Vue CLI is a powerful tool to scaffold and manage Vue.js projects. To install Vue CLI globally, run the following command in your terminal:
   npm install -g @vue/cli

Resources
To start learning Vuejs, we recommend watching the following comprehensive video course:
- https://youtu.be/VeNfHj6MhgA?si=03AZRH7rtFdxYqde
 
Projects After completing the video course, you will work on two practical projects to apply what you've learned.

### Project: Admin Dashboard with Vuetify

### Basic Features:
This project is a role-based admin dashboard application. It allows users to either log in as Admin or User, with specific features restricted based on their roles. The login system uses cookies to store session data, and middleware will be used to protect routes that require authentication.

1. Login and Registration:
 - Registration: Users can sign up with a username , password and confirm password.
 - Login: After signing up, users can log in using their credentials.

2. Roles and Dashboards:
 - Admin Login: If the Admin logs in with the correct credentials (e.g., username: "admin" and password: "admin123"), they will see the Admin Dashboard. The Admin can view and manage all users and data.
 - User Login: If any other user logs in with their credentials, they will only see the User Dashboard, where they can view basic information about themselves (like their profile and data). They won’t have access to admin features.

3. Role-Based Display:
 - Based on whether the user is an Admin or a User, the application will show different dashboards.

### Here are some additional resources to help you with Vuejs3:

- https://vuejs.org/guide/introduction.html

### Here are some additional resources to help you with Vuetify3 (Vuejs Framework):

- https://vuetifyjs.com/en/getting-started/installation/#installation

### Here are some additional resources to help you with State Management:

- Pinia Store : https://pinia.vuejs.org/introduction.html
- Vuex Store : https://vuex.vuejs.org/

Happy learning!
