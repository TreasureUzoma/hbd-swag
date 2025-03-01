# Happy Birthday 🎉

A delightful and customizable web application to send personalized happy birthday wishes to your friends, family, and colleagues! This project combines HTML, CSS, JavaScript, and JSON to create an interactive and engaging birthday greeting.

## Description 🎈

This project provides a fun and nerdy way to say "Happy Birthday!" Instead of a generic message, customize a unique webpage with the birthday person's name, a heartfelt message, and even a custom image. Watch as balloons float, confetti falls, and a personalized message appears, all set to a cheerful tune.

## Features 🌟

-   **Customizable Messages:** Tailor the greeting with personalized messages using `customize.json`.
-   **Dynamic Content:** JavaScript dynamically inserts the customized content into the HTML.
-   **Interactive Animations:** Engaging animations like confetti, balloons, and typing effects make the greeting more special.
-   **Music Integration:** Adds a festive background music to enhance the celebratory mood.
-   **Responsive Design:** Ensures the greeting looks great on various devices with Bootstrap and custom CSS.
-   **Name Parameter:** Use a URL parameter to dynamically set the name in the birthday message (e.g., `Happy Birthday.html?name=YourName`).

## Technologies Used 💻

| Category    | Technology                                     | Description                                                                                                                                                                                                                                 |
| :---------- | :--------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Frontend**  | HTML5                                          | Provides the structure and content of the webpage.                                                                                                                                                                                        |
|             | CSS3                                           | Styles the webpage, providing a modern and festive look.                                                                                                                                                                                     |
|             | Bootstrap                                      | Used for responsive design and pre-built CSS components.                                                                                                                                                                                     |
|             | JavaScript                                     | Handles dynamic content insertion, animations, and interactivity. Libraries like jQuery and Typed.js are also used.                                                                                                                         |
| **Data**      | JSON                                           | (`customize.json`) Stores customizable data such as greetings, names, and image paths.                                                                                                                                                       |
| **Animation** | GSAP (Greensock Animation Platform)           | Used for complex, high-performance animations in the `index.html` version.                                                                                                                                                              |
|             | Snowflakes.js                                  | Adds a snowflake effect to the `Happy Birthday.html` version.                                                                                                                                                                               |
|             | Typed.js                                       | Used for the typing animation effect in `Happy Birthday.html` version.                                                                                                                                                                      |
| **Other**     | Browser-Sync                                   | For live reloading during development.                                                                                                                                                                                                    |
|             | run-script-os                                  | Package to handle OS-specific start scripts.                                                                                                                                                                                                |
|             | Vercel                                         | Used for deploying and hosting the `index.html` version of the application.                                                                                                                                                               |
|             | JQuery                                          | Used for DOM manipulation and some animation in  `Happy Birthday.html` version                                                                                                                                                             |
|             | Live-server                                    | Used for Live-Reloading in `Happy Birthday.html` version                                                                                                                                                                                   |

## Installation ⚙️

Follow these steps to set up the project locally:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/TreasureUzoma/hbd-swag.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd hbd-swag
    ```

3.  **Install Dependencies (Optional):**
    - For index.html version no dependencies are required

    -  For Happy Birthday.html, no dependencies are required

4.  **Configure `customize.json`:**

    *   Modify the `customize.json` file to personalize the birthday message. You can change the greeting, name, wish text, and image path.

    ```json
    {
      "greeting": "Hey",
      "name": "Swag",
      "greetingText": "I really appreciate you my boss! Fr!",
      "wishText": "May the tech space Angel always Favour & be with you! ;)",
      "imagePath": "img/swag.jpg",
      "text1": "It's your birthday my bro!!!",
      "textInChatBox": "Happy birthday to you!! Swag!!!! Many many happy returns...",
      "sendButtonLabel": "Send",
      "text2": "That's what I was going to do.",
      "text3": "But then I stopped.",
      "text4": "I realised, I wanted to do something",
      "text4Adjective": "special",
      "text5Entry": "Because,",
      "text5Content": "You are Special",
      "smiley": ":)",
      "bigTextPart1": "S",
      "bigTextPart2": "O",
      "wishHeading": "Happy Birthday Swag!",
      "outroText": "Okay, now come back and tell me if you liked it.",
      "replayText": "Or click, if you want to watch it again.",
      "outroSmiley": ":)"
    }
    ```

## Usage 🚀

### index.html

1.  **Open `index.html` in your browser:**

    *   Simply double-click the file to open it directly in your browser.

### Happy Birthday.html

1.  **Open `Happy Birthday.html` in your browser:**

    *   Simply double-click the file to open it directly in your browser.

2.  **(Optional) Customize name:**
    -  You can change the name on the Happy Birthday page by adding `?name=YourName` to the URL. Example: `Happy