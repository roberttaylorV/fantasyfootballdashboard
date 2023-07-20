# football
# Fantasy Football Draft Dashboard

This project is a live updating dashboard for your fantasy football draft. It displays the currently selected user, their name, and the most recently picked player and the team they are going to. The dashboard fetches data from the Sleeper API and updates the information in real-time.

## Features

- Displays the currently selected user and their name.
- Shows the most recently picked player and the team they are going to.
- Updates the information dynamically using AJAX requests.
- Uses Python and Flask on the server-side.
- Utilizes the Sleeper API for retrieving draft and player data.

## Setup

1. Clone the repository:  git clone https://github.com/your-username/fantasy-draft-dashboard.git

2. Install the required dependencies:
pip install -r requirements.txt
3. Open `main.py` and replace `"draft_id"` with your actual draft ID.
4. Start the Flask server: python main.py

5. Access the dashboard in your web browser at `http://localhost:5000`.

## Project Structure

- `main.py`: Python script containing the Flask server code.
- `templates/`: Directory containing HTML templates for the dashboard.
- `static/`: Directory for static files (CSS, JavaScript, images, etc.).

## Usage

- The dashboard will automatically update every 5 seconds to fetch the most recent pick and team information.
- Customize the HTML and CSS templates to match your desired aesthetic.

## Dependencies

- Python 3.x
- Flask
- sleeperpy

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
