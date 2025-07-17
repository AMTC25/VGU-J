# VGU-Jaipur Student Portal

This is a simple, modern web-based student portal designed for VGU-Jaipur. It provides a basic interface for students to access various sections like a feed, academic modules, student groups, useful links, and settings. The portal is built using HTML and styled with Tailwind CSS, with interactive elements managed by vanilla JavaScript.

## Features

* **Responsive Design:** Utilizes Tailwind CSS for a mobile-first and responsive layout.
* **Tabbed Navigation:** Easy switching between different sections (Feed, Modules, Groups, Links, Code, Settings, Help) using a bottom navigation bar.
* **Dynamic Tab Highlighting:** The active tab button changes its background to white and its icon to red for clear visual feedback.
* **Module Management:** A dedicated "Modules" section with expandable/collapsible options (e.g., Edit Profile, Change Password).
* **External Links:** "Links" section provides quick access to important university resources like Webmail, Library, Academics, and Network Support.
* **Placeholder Sections:** "Code," "Settings," and "Help" sections are included as placeholders for future expansion.
* **Custom Scrollbar:** A subtle custom scrollbar for the vertical menu bar for improved aesthetics.

## Technologies Used

* **HTML5:** For the basic structure of the web pages.
* **Tailwind CSS:** A utility-first CSS framework for rapid UI development and styling.
* **JavaScript (Vanilla JS):** For handling tab switching, module expansion/collapse, and other interactive elements without external libraries.

## Getting Started

To view and run this project locally, follow these simple steps:

1.  **Clone or Download:**
    * **Clone the repository:**
        ```bash
        git clone <repository-url>
        ```
    * **Or, simply copy the `index.html` file:** You can just save the provided HTML code into a file named `index.html` on your computer.

2.  **Open in Browser:**
    * Navigate to the directory where you saved `index.html`.
    * Open the `index.html` file in your preferred web browser (e.g., Chrome, Firefox, Edge). You can usually do this by double-clicking the file.

That's it! Since all the CSS (Tailwind via CDN) and JavaScript are embedded directly in the HTML or linked via CDN, you don't need any build tools or a local server to get it running.

## Project Structure

The project currently consists of a single `index.html` file, which contains all the HTML, Tailwind CSS CDN link, and JavaScript logic.
