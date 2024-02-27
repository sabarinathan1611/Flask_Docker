# Flask Application Dockerization

This repository contains a Dockerfile and necessary configurations to containerize a Flask application.

## Prerequisites

- Docker installed on your machine. You can download and install Docker from [here](https://www.docker.com/get-started).

## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your_username/flask-docker.git
    ```

2. Navigate to the cloned directory:

    ```bash
    cd flask-docker
    ```

3. Build the Docker image:

    ```bash
    docker build -t flask-app .
    ```

4. Run the Docker container:

    ```bash
    docker run -p 5000:5000 flask-app
    ```

5. Access the Flask application in your browser by visiting `http://localhost:5000`.

## Project Structure

- `Dockerfile`: Contains instructions to build the Docker image for the Flask application.
- `requirements.txt`: Lists the Python dependencies required by the Flask application.
- `main.py`: Main entry point for the Flask application.
- `templates/`: Directory containing HTML templates for the Flask application.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

## License

This project is licensed under the [GNU GENERAL PUBLIC LICENSE](LICENSE).

