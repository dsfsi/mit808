# Project Overview

This is a Jekyll-based website for the Data Science Capstone course (MIT 808) at the University of Pretoria. The site provides information about the course, including the syllabus, learning outcomes, and a list of recommended readings and resources. It is built using the Reverie Jekyll theme.

The website is not the official course platform, but rather a public-facing informational site. The official course materials are managed through a separate system called ClickUP.

# Key Files

*   `_config.yml`: The main Jekyll configuration file. It contains settings for the site's title, author, description, and various Jekyll plugins.
*   `index.html`: The homepage of the website, which provides a welcome message and a brief overview of the course.
*   `_pages/`: This directory contains the main pages of the website, such as "About", "Readings", and "Resources".
*   `_sass/`: This directory contains the Sass files used to style the website.
*   `assets/`: This directory contains static assets like JavaScript files and the main stylesheet.
*   `images/`: This directory contains images used throughout the website.

# Building and Running

This is a Jekyll-based website. To build and run it locally, you will need to have Ruby and Jekyll installed.

1.  **Install Jekyll and Bundler:**

    ```bash
    gem install jekyll bundler
    ```

2.  **Install dependencies:**

    ```bash
    bundle install
    ```

3.  **Build and run the server:**

    ```bash
    bundle exec jekyll serve
    ```

    The site will be available at `http://localhost:4000`.

# Development Conventions

The website follows standard Jekyll conventions. Content is written in Markdown, and the site's layout and styling are defined using HTML, Sass, and Liquid templates.

*   **Pages:** New pages can be added to the `_pages` directory.
*   **Styling:** Custom styles can be added to the `_sass` directory. The main stylesheet is located at `assets/style.scss`.
