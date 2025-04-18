# Tracker App 🐳

A containerized web application built as part of a Docker learning exercise.

## 🚀 Features
- Dockerized Node.js (or Python/.NET/etc.) app
- Lightweight and portable
- Easy to run with one command

## 🛠️ Tech Stack
- Docker
- Node.js (or relevant tech)
- Express (or relevant framework)

## 📦 Getting Started

### Prerequisites
- [Docker](https://www.docker.com/)
- (Optional) [Docker Compose](https://docs.docker.com/compose/)

### Run the App

```bash
# Build the image
docker build -t tracker-app .

# Run the container
docker run -p 3000:3000 tracker-app

