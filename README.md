# URL Shortener using Flask

This is a simple URL shortener web application built with Flask, a Python web framework. It allows users to enter a long URL and generates a shorter version of it, making it easier to share and manage links.

## Features

- Shorten long URLs to create compact links.
- Redirects users from the shortened URL to the original long URL.
- Stores the mappings between shortened and original URLs in a JSON file for persistence.
- Uses a randomly generated alphanumeric string as the short URL.

## Installation

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your_username/url-shortener-flask.git
   ```

2. Install the required dependencies using pip:

   ```
   pip install flask
   ```

## Usage

1. Run the Flask application:

   ```
   python app.py
   ```

2. Open your web browser and navigate to `http://localhost:5000` to access the URL shortener web interface.

3. Enter a long URL in the input field and click the "Shorten" button. You will receive a shortened URL.

4. Copy the shortened URL and use it to redirect to the original long URL.

## Files

- `app.py`: The main Flask application file containing the URL shortener logic.
- `urls.json`: A JSON file that stores the mappings between shortened and original URLs.
- `templates/index1.html`: HTML template for the web interface.

## Customization

You can customize the behavior and appearance of the URL shortener by modifying the Flask application and the HTML template:

- To change the length of the shortened URL, you can modify the `generate_short_url` function in `app.py`.
- To customize the HTML template, edit the `templates/index1.html` file to change the layout and design of the web interface.

## Contributions

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or create a pull request on the GitHub repository.

Enjoy using this simple URL shortener built with Flask! If you have any questions or need assistance, feel free to reach out.
