# Flask Blog Application 📝

This project is a simple blog application built with Flask. It uses dynamic routing, templating, and an external API to fetch blog posts. The application demonstrates how to use Python classes to organize data and Flask for rendering dynamic HTML templates.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Setup and Installation](#setup-and-installation)
- [File Structure](#file-structure)
- [Usage](#usage)

## Overview

The Flask Blog Application allows users to view a list of blog posts and navigate to individual post details. Blog data is fetched from a remote API and dynamically displayed on the website.

## Features

- Fetches blog posts from an external API (`npoint.io`).
- Displays a list of blog posts on the home page.
- Allows navigation to individual posts with detailed content.
- Uses custom CSS for styling.

## Technologies

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS
- **Data Source**: JSON data from an API
- **Styling**: Custom CSS and Google Fonts

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/quangminhnguyen/flask-blog.git
   cd flask-blog
   ```

2. **Install Dependencies**: Ensure you have Python installed. Create a virtual environment and install the required dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   pip install flask requests
   ```

3. **Run the Application:** Execute the Flask application:
   ```bash
   python main.py
   ```

4. **Access the Application**: Open your web browser and navigate to:
   ```bash
   [python main.py](http://127.0.0.1:5000/)
   ```

## File Structure

```bash
flask-blog/
│
├── main.py            # Main Flask application file
├── post.py            # Class definition for blog posts
├── templates/         # HTML templates
│   ├── index.html     # Home page template
│   └── post.html      # Individual post template
├── static/
│   └── css/
│       └── styles.css # Custom CSS for styling
└── README.md          # Documentation
```

## Usage

1. **View All Blog Posts**:
Access the home page to see a list of all blog posts with their titles and subtitles.

2. **View Post Details**:
Click on the "Read" link for any post to view its full content.

3. **Customize Styles**:
Modify `static/css/styles.css` to update the application's appearance.

4. **Update Blog Data Source**:
Replace the `blog_url` variable in `main.py` with a different API endpoint to use another set of blog posts.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
