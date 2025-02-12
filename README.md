# My Favorite Football Team

## Overview

This project dynamically displays information about the Argentina 1986 World Cup-winning football team. It allows users to view player details and filter them based on specific criteria using a dropdown menu.

## Features

- Displays the team name, sport type, World Cup-winning year, and head coach.
- Lists all players with details including position, number, and nickname.
- Filters players based on position or nickname using a dropdown menu.
- Uses JavaScript ES6+ features like destructuring and `Object.freeze()` to prevent modifications.

## Technologies Used

- HTML
- CSS
- JavaScript (ES6+)

## Project Structure

```
|-- index.html       # Main HTML structure
|-- styles.css       # CSS styling
|-- script.js        # JavaScript logic
|-- README.md        # Project documentation
```

## Installation & Usage

1. Clone or download the repository.
2. Open `index.html` in a web browser.
3. Use the dropdown menu to filter players by position or nickname.

## Functionality

- The `myFavoriteFootballTeam` object contains details of the Argentina 1986 World Cup squad.
- The `setPlayerCards()` function dynamically generates player cards based on the selected filter.
- Event listeners handle dropdown menu interactions to update the displayed players.

## How It Works

1. The JavaScript script fetches and displays team details in designated HTML elements.
2. A dropdown menu allows filtering players by their position or those with a nickname.
3. The filtered results are displayed dynamically without reloading the page.

## Future Improvements

- Add more teams for comparison.
- Implement search functionality to find specific players.
- Enhance UI with animations and styling.

## License

This project is open-source and available for use under the MIT License.

## Author

Developed by Elijah Ackah
