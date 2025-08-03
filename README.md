# ft_transcendence

A full-stack multiplayer web application built as the final project of the 42 curriculum. **ft_transcendence** integrates real-time gaming, user authentication, chat systems, ranking, and social features into one seamless platform—an elevated take on the classic Pong game.

## 🧠 Project Overview

The goal of this project is to demonstrate proficiency in full-stack web development using modern frameworks and technologies. Users can register, play Pong online against other players, chat, add friends, track your game stats and create tournaments.

## ⚙️ Features

- 🎮 **Multiplayer Pong Game** — Real-time, online gameplay 1v1 or create a tournament with friends  
- 👤 **Authentication** — 2FA, OAuth, JWT-based auth  
- 📬 **Live Chat** — Real-time messaging and channels  
- 🏅 **Leaderboard & Stats** — Track wins and game history
- 🧱 **Modular Architecture** — Easily extendable components  
- 📱 **Responsive UI** — Works across devices  

## 🏗️ Architecture

- **Frontend**: Vue.js 
- **Backend**: Python Django, REST APIs and WebSockets  
- **Database**: PostgreSQL  
- **Authentication**: OAuth2, JWT, optional 2FA via TOTP  
- **Deployment**: Docker & Docker Compose (with optional NGINX/SSL)  
- **CI/CD**: [GitHub Actions / other] for testing and deployment pipelines  

## 📦 Tech Stack

- `PostgreSQL`  
- `WebSockets`  
- `Vue`
- `Docker`, `Docker Compose`  
- `Socket.io`  

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/kris-bo/ft_transcendence.git
cd ft_transcendence

# Create a .env file from the sample
cp .env.example .env

# Build and run the containers
docker-compose up --build
