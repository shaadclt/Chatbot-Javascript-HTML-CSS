/**
 * JavaScript Chatbot with OpenAI GPT-3.5 Turbo
 *
 * A simple chatbot implementation using JavaScript and integration with the OpenAI GPT-3.5 Turbo model.
 *
 * Features:
 * - User-friendly chat interface.
 * - Integration with OpenAI GPT-3.5 Turbo.
 * - Responsive design for mobile and desktop.
 *
 * Prerequisites:
 * - Modern web browser
 * - Code editor (e.g., Visual Studio Code)
 *
 * Installation:
 * 1. Clone the repository:
 *    ```
 *    git clone https://github.com/your-username/your-repo.git
 *    ```
 * 2. Open the project in your code editor.
 * 3. Open `index.html` in your web browser.
 *
 * Usage:
 * 1. Open `index.html` in a web browser.
 * 2. Interact with the chatbot by entering messages in the input field.
 * 3. Explore the chatbot's responses.
 *
 * Configuration:
 * - Update the `API_KEY` variable in `script.js` with your actual OpenAI GPT-3.5 Turbo API key.
 *   ```javascript
 *   const API_KEY = "PASTE-YOUR-API-KEY"; // Paste your API key here
 *   ```
 *
 * Customization:
 * - Feel free to customize the chatbot appearance and behavior by modifying the HTML, CSS, and JavaScript files.
 *
 * Contributing:
 * - Fork the repository.
 * - Create a new branch for your feature:
 *   ```
 *   git checkout -b feature/your-feature
 *   ```
 * - Commit your changes:
 *   ```
 *   git commit -m "Add your feature"
 *   ```
 * - Push to the branch:
 *   ```
 *   git push origin feature/your-feature
 *   ```
 * - Open a pull request.
 *
 * License:
 * - This project is licensed under the MIT License.
 *
 * Acknowledgments:
 * - BootstrapMade.com for the original template.
 *
 * Contact:
 * - For any inquiries or feedback, please contact [your-email@example.com].
 */

// JavaScript code for the chatbot
const chatbotToggler = document.querySelector(".chatbot-toggler");
const closeBtn = document.querySelector(".close-btn");
const chatbox = document.querySelector(".chatbox");
const chatInput = document.querySelector(".chat-input textarea");
const sendChatBtn = document.querySelector(".chat-input span");

// ... (rest of the code)
