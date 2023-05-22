# Pollster Django App

Pollster is a Django application that allows you to create and manage polls. Users can vote on the available options and view the results in real-time.

## Features

- Create and manage multiple polls with custom questions and options.
- Allow users to vote on the available options.
- Real-time updating of poll results.
- Admin dashboard for managing polls and viewing voting statistics.

## Installation

1. Clone this repository to your local machine.
2. Create a virtual environment and activate it.
3. Install the required dependencies by running `pip install -r requirements.txt`.
4. Set up the database by running `python manage.py migrate`.
5. (Optional) Load sample data by running `python manage.py loaddata sample_data.json`.
6. Start the development server with `python manage.py runserver`.

## Usage

1. Access the application in your web browser at `http://localhost:8000`.
2. Use the admin dashboard at `http://localhost:8000/admin` to create and manage polls.
3. Users can view and vote on polls on the home page.
4. Real-time updates of poll results are displayed as votes are cast.

## Configuration

The following environment variables can be configured:

- `SECRET_KEY`: Django secret key.
- `DEBUG`: Set to `True` to enable debug mode (not recommended for production).
- `DATABASE_URL`: URL of the database connection.

## Contributing

Contributions are welcome! If you find any issues or want to add improvements, please submit a pull request. Follow the contribution guidelines.

## License

This application is released under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements

This application was inspired by the Django Polls tutorial.

---

Please feel free to contact us if you have any questions or feedback. Happy polling!
