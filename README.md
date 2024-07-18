# Portfolio Website

This repository contains the code for a personal portfolio website built using HTML, CSS, JavaScript, and Django. The website showcases projects, skills, and contact information.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- Home page
- About section
- Projects section showcasing completed work
- Skills section highlighting technical abilities
- Contact form for getting in touch

## Technologies Used

- **Frontend:**
  - HTML
  - CSS
  - JavaScript

- **Backend:**
  - Django

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/sharadsisodia/portfolio-website.git
    cd portfolio
    ```

2. Set up a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```sh
    python manage.py migrate
    ```

5. Run the development server:
    ```sh
    python manage.py runserver
    ```

6. Open your browser and navigate to `http://127.0.0.1:8000`.

## Usage

- Modify the HTML, CSS, and JavaScript files in the `static` directory to update the frontend.
- Update Django templates in the `templates` directory.
- Add or update projects and other content in the Django admin interface.

## Project Structure
portfolio/
│
├── portfolio/
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ └── ...
│
├── static/
│ ├── css/
│ ├── js/
│ └── images/
│
├── templates/
│ ├── resume.html
│ ├── index.html
│ └── ...
│
├── manage.py
├── requirements.txt
└── README.md

## License

This project is licensed under the MIT License.

## Contact

- **Name:** Sharad Sisodia
- **Email:** sharadsisodia222@gmail.com
