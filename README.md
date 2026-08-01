# Restaurant Website

A responsive and dynamic restaurant website built with HTML, CSS, Bootstrap, and JavaScript.

This project was developed as part of the **HTML, CSS, and JavaScript for Web Developers** course on Coursera. It demonstrates responsive web design, DOM manipulation, AJAX requests, and dynamic content rendering.

https://kowrosh.github.io/Restaurant-courseraa/

## Features

* Responsive design for desktop, tablet, and mobile devices
* Dynamic restaurant menu
* Multiple food categories
* Detailed menu items with prices and descriptions
* AJAX-based data loading
* JSON data processing
* Random menu category displayed on the homepage
* Dynamic page content without full-page reloads

## Technologies Used

* HTML5
* CSS3
* Bootstrap
* JavaScript
* AJAX
* JSON
* DOM Manipulation
* Responsive Web Design

## How It Works

The website sends asynchronous HTTP GET requests to retrieve restaurant menu data from an external API.

The returned JSON data is processed using JavaScript and dynamically inserted into the webpage.

Reusable HTML snippets are used as templates for menu categories and food items. JavaScript replaces the placeholders inside these templates with real information such as:

* Food name
* Description
* Price
* Portion size
* Image
* Category name

The homepage also selects a random menu category and displays it as a featured category.

## Project Structure

```text
Restaurant-courseraa/
│
├── css/
│   └── styles.css
│
├── fonts/
│
├── images/
│
├── js/
│   ├── ajax-utils.js
│   └── script.js
│
├── snippets/
│   ├── categories-title-snippet.html
│   ├── category-snippet.html
│   ├── home-snippet.html
│   ├── menu-item.html
│   └── menu-items-title.html
│
└── index.html
```

## Running the Project

Clone the repository:

```bash
git clone https://github.com/kowrosh/Restaurant-courseraa.git
```

Open the project folder:

```bash
cd Restaurant-courseraa
```

Then open `index.html` in your browser.

For the best result, run the project using a local development server such as the Live Server extension in Visual Studio Code.

## What I Learned

Through this project, I improved my understanding of:

* Creating responsive web layouts
* Using Bootstrap components and grid systems
* Manipulating the DOM with JavaScript
* Sending asynchronous HTTP requests
* Working with JSON data
* Dynamically generating HTML content
* Organizing frontend project files
* Building reusable HTML templates

## Repository

[Restaurant-courseraa](https://github.com/kowrosh/Restaurant-courseraa)

## Acknowledgment

This project was developed as part of the Coursera course:

**HTML, CSS, and JavaScript for Web Developers**
Johns Hopkins University
