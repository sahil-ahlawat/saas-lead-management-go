# SaaS Lead Management API

This project is a Go-based API for managing leads, built with Fiber, MySQL, and Redis, all running in Docker containers.

## Prerequisites

*   Docker
*   Docker Compose

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone <repository-url>
    cd saas-lead-management-go
    ```

2.  **Build and start the services:**

    ```bash
    docker-compose up -d --build
    ```

## Accessing the Services

*   **API:** [http://localhost:3000](http://localhost:3000)
*   **MySQL Dashboard (Adminer):** [http://localhost:8080](http://localhost:8080)
    *   **System:** `MySQL`
    *   **Server:** `sa_sass_db`
    *   **Username:** `root`
    *   **Password:** `rootpassword`
    *   **Database:** `lead_management`
*   **Redis Dashboard (Redis Commander):** [http://localhost:8081](http://localhost:8081)
