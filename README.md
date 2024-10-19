# Open Music API - Consumer

Proyek ini adalah consumer untuk proyek [Open Music API](https://github.com/callmeaxeload/openmusic-api).

## How to run

**Make sure project [Open Music API](https://github.com/callmeaxeload/openmusic-api) are running in another Terminal/VS Code window.**

Create an **.env** file in the root directory of project and fill it with variables

### - Locally

- Prerequisites

  - **Node.js** installed on your local machine. You can download it from [nodejs.org](https://nodejs.org/).
  - **Postgresql** database installed on your local machine. You can download it from [postgresql.org](https://www.postgresql.org/download/).
  - **Redis** for caching installed on your local machine. You can download it from [redis.io](https://redis.io/downloads/).
  - **RabbitMQ** for message broker installed on your local machine. You can download it from [rabbitmq.com](https://www.rabbitmq.com/docs/download).

- Installation

  Clone the repository and install dependencies.

  ```bash
  git clone <repository-url>
  cd <project-directory>
  npm install
  ```

- Running

  Make sure you have started your database server and then run this

  ```bash
  npm run dev
  ```

