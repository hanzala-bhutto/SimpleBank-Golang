# SimpleBank-Golang

SimpleBank-Golang is a backend web service for a simple bank, developed in Go. It provides APIs for account management, balance tracking, and money transfers.

## Features
- **Account Management**: Create and manage bank accounts.
- **Transaction Recording**: Record balance changes for accounts.
- **Money Transfers**: Perform transfers between accounts.

## Technologies
- **Language**: Go
- **Database**: PostgreSQL
- **API**: Gin
- **Auth**: JWT, PASETO
- **Other Tools**: Docker, Viper, migrate, sqlc, Gomock

## Getting Started

### Prerequisites
- Go 1.18+, Docker, PostgreSQL

### Installation
1. Clone the repository:  
   `git clone https://github.com/hanzala-bhutto/SimpleBank-Golang.git`
2. Navigate to the directory:  
   `cd SimpleBank-Golang`
3. Start the database:  
   `docker-compose up -d`
4. Run migrations:  
   `make migrateup`
5. Start the app:  
   `make server`

## Project Structure
- `db/`: Database schema & queries
- `util/`: Utility functions
- `main.go`: Application entry point

## Acknowledgements
Based on the [Backend Master Class](https://github.com/techschool/simplebank) by TECH SCHOOL.
