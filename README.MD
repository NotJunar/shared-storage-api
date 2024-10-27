

# Emulated API in HTML

This project demonstrates a proof of concept for emulating a minimum API using HTML and JavaScript. It includes three HTML files that showcase how to store and retrieve data using `localStorage`, enabling communication between different pages on the same origin.

## Project Structure

- **addUser.html**: A page where users can input a name to add to the user list. The entered names are stored in `localStorage`.
- **viewUsers.html**: A page that retrieves and displays the list of users stored in `localStorage`.
- **APIUsers.html**: A standalone version that mimics API-like functionality for adding and viewing users, all within a single HTML page.

## Features

- **Data Storage**: Uses `localStorage` to persist user data across page reloads and between different HTML files.
- **User Management**: Allows adding new users and viewing the existing user list.
- **Minimal Setup**: No backend server is required; everything runs client-side in the browser.

## Getting Started

1. **Clone the Repository** (if applicable) or create the HTML files as described above.
2. **Open the HTML files** in your web browser:
   - Open `addUser.html` to add users.
   - Open `viewUsers.html` to view the list of added users.
   - Open `APIUsers.html` is a combination of the html listed above. I made this version first ^

## Usage

- **To Add a User**:
  - Navigate to `addUser.html`, enter a name in the input field, and click "Add User." The user will be stored in `localStorage`.
  
- **To View Users**:
  - Navigate to `viewUsers.html` and click "Get Users" to see the list of all users added.

- **Standalone Version**:
  - Use `APIUsers.html` to manage users in a single page.

## Conclusion

This project serves as an example of how to emulate API behavior using just HTML and JavaScript. It highlights the capability of `localStorage` for simple data persistence in a client-side environment.

## License

This project is open source and available under the [MIT License](LICENSE).

