# IPL-Performance-Portal

## Description 

The IPL-Performance-Portal is a console-based Java application designed to provide detailed information about players of three prominent IPL teams: Mumbai Indians (MI), Chennai Super Kings (CSK), and Royal Challengers Bangalore (RCB). Users can access information like player names, jersey numbers, total runs scored, and wickets taken. The application incorporates Object-Oriented Programming (OOP) principles and a multi-layered architecture for modularity and scalability.

## Features
### Team Selection Menu:
Displays a menu for the user to select one of the three teams or exit the application.

### Player Information Retrieval:
- Fetches a list of players for the selected team, including:
- Player Name: Name of the player.
- Jersey Number: Unique identifier for the player.
- Runs: Total runs scored by the player in IPL matches.
- Wickets: Total wickets taken by the player in IPL matches.

### Dynamic Console Interaction:
- The application uses Scanner for real-time user input.
- Menu-driven flow to enhance user interaction.

## Technologies Used
- **Programming Language**: Java
- **Architecture**:: Multi-layered (Entity-DAO-Service-Controller-Client)
- **IDE**: Any Java-compatible IDE like Eclipse

## Project Structure  
```plaintext
IPL-Performance-Portal
├── src
│   ├── entity       # Data classes to represent the player data.
│   ├── dao          # Handles data-related logic for teams 
│   ├── service      # Contains business logi
│   ├── controller   # Manages communication between the client and service
│   └── client       # Entry point of the application 
└── README.md        # Project documentation


