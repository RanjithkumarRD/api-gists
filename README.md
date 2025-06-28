# GitHub Gists API Server

This is a simple Python Flask-based HTTP web server that responds to requests on the route `/<user>` by returning a list of the specified GitHub user's publicly available Gists.

## Installation

1. Clone the repository:

       git clone https://github.com/EqualExperts-Assignments/equal-experts-colorful-alert-industrious-recommendation-f965a62ea363.git

2. Create a virtual environment and activate it:

        python -m venv venv
        source venv/bin/activate  # On Windows use `venv\\Scripts\\activate`

3. Install dependencies:

        pip install -r requirements.txt

4. Run the server:

        python app.py

        The server will start on http://localhost:8080.

## Usage

        **Endpoint** GET /<user>
        **Example** GET http://localhost:8080/octocat
