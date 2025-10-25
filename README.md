# JobFind

JobFind is a web application designed to facilitate job searching and networking. It provides features for job listings, direct messaging, notifications, and user profiles.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contact Information](#contact-information)


## Installation

To set up the project locally using Docker, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd JobFind
   ```
3. Build and start the Docker containers:
   ```bash
   docker-compose up -d
   ```
   This command will build the Docker images and start the containers in detached mode.

4. Access the application:
   - The web application will be available at `http://localhost:5001`.
   - The MySQL database will be accessible on port `3307`.

## Usage

To stop the application, use the following command:

```bash
docker-compose down
```

This command will stop and remove the containers.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact Information

Contact: [Erdison Malko](mailto:erdisonmalko@gmail.com).

