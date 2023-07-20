
# Live Draft Dashboard

Author: Robert Taylor

## Description

This project is a simple Flask web application that provides a live draft dashboard for a sports draft. It displays the details of the most recent pick, such as the player's name, team name, round, pick number, position, and team owner. The dashboard updates these details in real time every 0.1 seconds.

## Dependencies

The following Python packages are required to run this application:

- Flask
- sleeperpy

You can install these packages using pip:

```
pip install Flask sleeperpy
```

## Setup and Running the Application

1. Make sure you have Python installed on your machine. You can check this by running `python --version` in your terminal. If Python is not installed, you can download it from the official website: https://www.python.org/.

2. Clone this repository to your local machine.

3. Navigate to the project directory in your terminal.

4. Install the required dependencies using pip:

    ```
    pip install -r requirements.txt
    ```

    Note: If the `requirements.txt` file is not available, you can install the dependencies manually using the command provided in the Dependencies section above.

5. Run the Flask application:

    ```
    python main.py
    ```

6. Open your web browser and go to `http://localhost:5000` to view the live draft dashboard.

## Using the API

The application provides an API endpoint (`'/api/recent_pick'`) that returns a JSON object with the details of the most recent pick. You can access this endpoint by making a GET request to `http://localhost:5000/api/recent_pick`.

---

Please note that this README assumes that the Flask application will be run on the local machine (localhost) and the default Flask port (5000) will be used. If you plan to deploy this application to a server or run it on a different port, you'll need to update the URLs accordingly.
