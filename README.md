# 🚀 Microservices Portfolio

A containerized microservices ecosystem orchestrated via a central Docker Compose setup. This repository acts as the umbrella infrastructure controller for the Lending Library application suite.

## 🏛️ Architecture & Services

The system consists of three core microservices connected via a dedicated internal bridge network (`library-net`):

| Service | Technology | Port | Description |
| :--- | :--- | :--- | :--- |
| **Frontend** (`lending-library-2`) | React / Nginx | `80:80` | User interface and client application |
| **Backend** (`library-app`) | Java 17 / Spring Boot, Maven | `8080:8080` | Core business logic and database connectivity |
| **AI Service** (`lending-library-ai`) | Python 3.11, FastAPI | `8000:8000` | AI microservice handling intelligent features |

---

## 🛠️ Prerequisites

* [Docker](https://www.docker.com/) & [Docker Compose](https://docs.docker.com/compose/) installed on your machine.

---

## 🚀 Quick Start

1. Clone the repository and navigate to the root folder:
   ```bash
   cd portfolio
