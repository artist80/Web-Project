# Web Project with Popular Website Integration

This is a simple web project using Flask to integrate popular websites like YouTube, TikTok, and Instagram into a single-page application. The project displays the selected website in an iframe within the same page.

## Requirements

- Python 3.x
- Flask

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/web_project.git
    cd web_project
    ```

2. Create a virtual environment and activate it:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install Flask
    ```

## Usage

1. Run the Flask application:

    ```bash
    python app.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000/`.

3. Click on the links in the header to navigate to YouTube, TikTok, or Instagram. The selected website will be displayed in an iframe on the same page.

## File Descriptions

- `app.py`: The main Flask application file, containing routes for the main page and each popular website.
- `templates/index.html`: The main HTML file containing the header, navigation, and content area.
- `templates/iframe.html`: The HTML file used to display the selected website in an iframe.
- `static/css/style.css`: The CSS file for styling the web pages.
- `static/images/logo.png`: The logo image displayed in the header.
- `LICENSE`: The MIT License file.
- `README.md`: This README file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## Acknowledgements

- [Flask](https://flask.palletsprojects.com/) - The web framework used.
- [CompCit](https://www.compcit.com) - Logo source.
