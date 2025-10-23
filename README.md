
# Coding-Bits

*A mini web project built using HTML, CSS and JavaScript*

---

## Table of Contents

* [Project Overview](#project-overview)
* [Features](#features)
* [Getting Started](#getting-started)

  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Running the Project](#running-the-project)
* [Project Structure](#project-structure)
* [How It Works](#how-it-works)
* [Technologies Used](#technologies-used)
* [Future Enhancements](#future-enhancements)
* [License / Contact](#license-contact)

---

## Project Overview

The **Coding-Bits** project is a simple but functional web-application that lets users log in and take a quiz.
It’s intended as a front-end exercise — focusing on UI, interactive behaviour, and basic form handling.

---

## Features

* A **login page** where users are prompted for credentials.
* A **quiz interface** (quiz.html) where multiple-choice questions are answered.
* Clean, responsive styling via CSS (style.css & loginStyle.css).
* Dynamic logic using JavaScript (script.js) to track answers and present results.
* Organized folder structure with separate pages for login, quiz, styles and images.

---

## Getting Started

### Prerequisites

You’ll need:

* A modern web browser (Chrome, Firefox, Edge etc)
* A code editor if you wish to open/edit the files (VS Code, Sublime, etc)
* (Optional) A local HTTP server for testing — though opening `index.html` directly works for most cases

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/Saadsaleem17/Coding-Bits.git  
   ```
2. Navigate into the project folder

   ```bash
   cd Coding-Bits  
   ```

### Running the Project

* Open `index.html` in your browser to view the landing/login page.
* Use the login page to proceed to the quiz.
* On the quiz page (`quiz.html`), answer the questions and see your outcome.

---

## Project Structure

```
Coding-Bits/
 ├── images/             ← image assets used in UI  
 ├── subjects/           ← optional folder (if used)  
 ├── index.html          ← main entry / landing page  
 ├── login.html          ← login UI  
 ├── loginStyle.css      ← CSS specific to login page  
 ├── quiz.html           ← quiz UI  
 ├── style.css           ← general styling for quiz / rest of app  
 ├── script.js           ← JavaScript logic for quiz & interactivity  
 └── .gitattributes  
```

---

## How It Works

* **Login Flow**: User begins at `index.html`, is sent to `login.html`, enters credentials (client-side only) and is allowed to continue to `quiz.html`.
* **Quiz Logic**: In `script.js`, JavaScript handles question display, user answer selection, score calculation, and result display.
* **Styling**: CSS files manage layout, colours, fonts, responsive behaviour. Styles are separated by page for clarity (login vs quiz).
* **Navigation**: Simple hyperlinks or JS-redirects move user between pages depending on state (logged in, quiz completed, etc).

---

## Technologies Used

* **HTML5** — for the structure and semantics of pages
* **CSS3** — for styling, layout and responsive design
* **JavaScript (vanilla)** — for interactive logic, DOM manipulation and score tracking
* Optionally: any browser DevTools for debugging/test

---

## Future Enhancements

Here are some ideas to take this further:

* Add **user authentication** (backend) so login becomes real and persistent.
* Add a **database or JSON file** to store quiz questions, so they’re not hard-coded.
* Style enhancements: theme toggle (dark/light), better animations, mobile-first layout.
* Add **timer** functionality for the quiz.
* Add **progress tracking**, multiple quizzes/categories, leaderboard.
* Improve accessibility, make UI multilingual.

---

## License / Contact

Feel free to fork this repository, adapt and build upon it.
If you’d like to reach me for feedback, contributions or ideas — find me on GitHub under **Saadsaleem17**.
Enjoy coding and building — happy to help if you want to expand this further.
