# CodeLearn

CodeLearn is a web application designed to help users learn programming languages and practice coding through interactive challenges. The project utilizes the Gemini API to provide step-by-step learning resources and to validate user-submitted code for programming challenges.

## Key Features

- **Learning Programming Languages:**
  - Users can select a programming language they want to learn.
  - Step-by-step guidance is generated using the Gemini API.
  - Provides links to tutorials, documentation, and coding exercises.

- **Programming Challenges:**
  - Users can request programming challenges in their chosen language.
  - Submit solutions directly on the webpage.
  - Automated code checking using the Gemini API provides feedback on correctness.

## Technologies Used

- **Front-end:**
  - HTML
  - CSS
  - JavaScript

- **Back-end:**
  - Gemini API for generating learning guides and checking code

## File Structure

- `page1.html`, `page1.css`, `page1.js`: Files for learning programming languages.
- `page2.html`, `page2.css`, `page2.js`: Files for programming challenges.
- Additional assets like images (`ba.png`, `bot1.png`, `buttonimg.png`, `logo.png`, `reload.gif`) and fonts (`monaco.woff`).

## Getting Started

To run the website locally:

1. Clone the repository:
   ```
   git clone https://github.com/Surapanenisslakshmi/CodeLearn.git
   ```

2. Create an `env.js` file with your Gemini API key:
   ```javascript
   export const process = {
     env: {
       GEMINI_API_KEY: "YOUR_API_KEY_HERE"
     }
   };
   ```

3. Replace `"YOUR_API_KEY_HERE"` with your actual Gemini API key.

4. Open `page1.html` or `page2.html` in a web browser to start using the application.

## Contributing

Contributions are welcome! If you'd like to contribute to CodeLearn, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
```


