# BeFit
# [live](https://befit-tracker.vercel.app/)


Befit is a fitness tracking application built using Next.js and Tailwind CSS for the front-end and Python FastAPI for the back-end. It allows users to track their fitness goals, monitor their progress, meditation and view workout history. With a sleek and intuitive interface, Befit is perfect for those looking to take control of their fitness journey.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

To use Befit locally on your machine, follow these steps:

1. Clone or download this repository to your local machine.
2. Open your terminal and navigate to the project directory.
3. To start the client side of the application, go to the `client` directory and run `npm install` to install all the required dependencies and then run `npm run dev` to start the development server.
4. To start the server side of the application, go to the `server` directory and run `pip install -r requirements.txt` to install all the required dependencies and then run `uvicorn main:app --reload` to start the server.

Note: For the server to function properly, you will need to create a `.env` file in the `server` directory with the following content:
DATABASE_URL=

Replace `<your-database-url>` with the URL to your Postgres database. If you don't have one yet, you can create one for free using services like Heroku.

## Usage

To use Befit, follow these steps:

1. Open your web browser and go to http://localhost:3000/.
2. Sign up for an account or log in to your existing account.
3. Set up your fitness goals and start tracking your progress.
4. Use the meditation feature to relax your mind and improve your mental health.
5. View your workout history to see how far you've come.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork this repository.
2. Create a new branch (`git checkout -b feature/<feature-name>`) and make your desired changes.
3. Commit your changes (`git commit -m "Add feature X"`).
4. Push to the branch (`git push origin feature/<feature-name>`).
5. Open a pull request and describe your changes.

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
