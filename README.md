# Password Protected Website 🔒

This is a simple password protected website that utilizes the `prompt()` function of JavaScript. The user is prompted to enter a password, and access to the website is granted only if the correct password is provided.

## Technologies Used 💻

- HTML
- CSS
- JavaScript

## How It Works 🛠️

1. When the user loads the website, a JavaScript function is triggered to prompt the user for a password.
2. The user enters a password in the prompt dialog.
3. The entered password is compared to a pre-defined password stored in the JavaScript code.
4. If the entered password matches the pre-defined password, the user is granted access to the website.
5. If the entered password does not match, the user is denied access and an error message is displayed.

## Getting Started 🚀

To run the password protected website locally, follow these steps:

1. Clone this repository to your local machine.
2. Open the `index.html` file in your preferred web browser.
3. The website will prompt you to enter a password.
4. Enter the correct password to access the website.

## Example Code 📝

```javascript
// Prompt the user for a password
var password = prompt("Please enter the password:");

// Define the correct password
var correctPassword = "mysecretpassword";

// Compare the entered password with the correct password
if (password === correctPassword) {
  // Access granted
  alert("Welcome! You have successfully logged in.");
  // Additional code to display the protected content of the website
} else {
  // Access denied
  alert("Incorrect password. Please try again.");
}
```

## License 📄

This project is licensed under the [MIT License](LICENSE).

Feel free to customize and use this password protected website for your own purposes.

## Contributions 🙌

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Resources 📚

- [MDN Web Docs - prompt()](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt)
- [W3Schools - JavaScript Prompt](https://www.w3schools.com/jsref/met_win_prompt.asp)

## Acknowledgements 🌟

- [OpenAI](https://openai.com/) for providing the AI technology to generate this README template.
- [GitHub](https://github.com/) for hosting this repository and enabling collaboration.
