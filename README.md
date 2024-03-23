# Cosmos API

## Overview
The **Cosmos API** provides access to information about the universe, including stars, asteroids, comets, galaxies, and planetary systems.

## Technologies Used
- **.NET 8**: The API is developed using .NET 8, the latest version of the .NET framework.
- **GraphQL for .NET**: The API utilizes the latest version of GraphQL for .NET to implement a flexible and efficient query interface.
- **Entity Framework 8**: Entity Framework 8 is used as the ORM (Object-Relational Mapping) framework to interact with the database.
- **PostgreSQL 16.2**: The database management system used to store the API's data. PostgreSQL 16.2 provides scalability, reliability, and advanced features for managing relational data.
- **AWS Hosting**: The API is hosted on Amazon Web Services (AWS), leveraging AWS's cloud infrastructure for scalability, reliability, and performance.

## License
This application is licensed under the [MIT License](https://opensource.org/licenses/MIT), allowing anyone to use, modify, and distribute the code for both commercial and non-commercial purposes, with attribution to the original author.

## Endpoints

### Universes
- `/universes`: Get information about all universes.
- `/universe/{universe-id}`: Get detailed information about a specific universe.

### Interstellar Stars
- `/universe/{universe-id}/stars`: Get information about interstellar stars within a universe.
- `/universe/{universe-id}/stars/{star-name}`: Get information about a specific interstellar star by name.
- `/universe/{universe-id}/stars/{star-id}`: Get information about a specific interstellar star by ID.

### Interstellar Asteroids
- `/universe/{universe-id}/asteroids`: Get information about interstellar asteroids within a universe.
- `/universe/{universe-id}/asteroids/{asteroid-id}`: Get information about a specific interstellar asteroid by ID.

### Interstellar Comets
- `/universe/{universe-id}/comets`: Get information about interstellar comets within a universe.
- `/universe/{universe-id}/comets/{comet-id}`: Get information about a specific interstellar comet by ID.

### Galaxies
- `/universe/{universe-id}/galaxies`: Get information about galaxies within a universe.
- `/universe/{universe-id}/galaxies/{galaxy-name}`: Get information about a specific galaxy by name.
- `/universe/{universe-id}/galaxies/{galaxy-id}`: Get information about a specific galaxy by ID.

### Rogue Stars
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stars`: Get information about rogue stars within a galaxy.
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stars/{star-id}`: Get information about a specific rogue star by ID.
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stars/{star-name}`: Get information about a specific rogue star by name.

### Rogue Planets
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/planets`: Get information about rogue planets within a galaxy.
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/planets/{planet-id}`: Get information about a specific rogue planet by ID.
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/planets/{planet-name}`: Get information about a specific rogue planet by name.

### Stellar Systems
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stellar-systems`: Get information about stellar systems within a galaxy.
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stellar-systems/{stellar-system-id}`: Get information about a specific stellar system by ID.
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stellar-systems/{stellar-system-name}`: Get information about a specific stellar system by name.

### Planets
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stellar-systems/{stellar-system-name or stellar-system-id}/planets`: Get information about planets within a stellar system.
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stellar-systems/{stellar-system-name or stellar-system-id}/planets/{planet-id}`: Get information about a specific planet by ID.
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stellar-systems/{stellar-system-name or stellar-system-id}/planets/{planet-name}`: Get information about a specific planet by name.

### Moons
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stellar-systems/{stellar-system-name or stellar-system-id}/planets/{planet-name or planet-id}/moons`: Get information about moons within a planet.
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stellar-systems/{stellar-system-name or stellar-system-id}/planets/{planet-name or planet-id}/moons/{moon-id}`: Get information about a specific moon by ID.
- `/universe/{universe-id}/galaxies/{galaxy-name or galaxy-id}/stellar-systems/{stellar-system-name or stellar-system-id}/planets/{planet-name or planet-id}/moons/{moon-name}`: Get information about a specific moon by name.
