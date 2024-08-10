# Dice Roll Game
Dice Roll Game where you have to guess any number, if your number is equivalent to what you thought then you will get a number, and if not then you will get a negative 1 number. 


https://github.com/user-attachments/assets/064415e7-e357-484b-bc89-dbbd26833e27


## Prerequisites

- [Node.js](https://nodejs.org/) (for simple start)
- [Docker](https://www.docker.com/) (for Docker Run)

## Getting Started

### Running the Game with npm 1

1. **Clone the repository:**
    ```sh
    git clone https://github.com/codewith-habib/Dice-Roll-Game.git
    cd Dice-Roll-Game
    ```

 2. **Install dependencies:**
    ```sh
    npm install
    ```   

3. **Start the development server:**
   ```sh
   npm run dev
   ```

4. **Open your browser:**
    Navigate to `http://localhost:3000` to play the game.


### Running the Game with Docker 

1. **Copy the docker-compose File:**
    ```sh
    name: dice-roll
    
    services:
      front:
        image: habib80246/dice-roll-game
        container_name: roll-dice-game
        ports:
          - '8080:80' #You can change the 8080 port if you want
        restart: unless-stopped
    
2. **Run the Command:**
     ```sh
    docker-compose up
    ```
     
2. **Open your browser:**
    Navigate to `http://localhost:8080` to play the game.


### Master Docker with My YouTube Channel:

If you want to master Docker and learn more about containerization, don't forget to check out my YouTube channel where I teach a complete Docker course

[Subscribe to DevMastery on YouTube](https://www.youtube.com/@devmastery46)
