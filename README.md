# Try Docker Compose

This example is inspired by the official Docker documentation, and it serves as a straightforward illustration to help you understand how Docker Compose functions.

## Prerequisites

- You need to have Docker Engine and Docker Compose on your machine.

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Saidelariss/Try-Docker-Compose.git

1. Change into the project directory:

   ```bash
   cd Try-Docker-Compose

1. Build and run your app with Compose:

   ```bash
   docker compose up

Docker Compose fetches a Redis image, generates an image for your code, initiates the services you've specified, and includes a bind mount for the web service. This is where the value of Docker Compose becomes evident, as it eliminates the need for manual intervention in these tasks.

4. Access the application in your web browser at http://localhost:8000.
