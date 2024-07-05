˚ ༘♡ ⋆｡˚˚ ༘♡ ⋆｡˚˚ ༘♡ ⋆｡˚
# Robot Movement Control Interface

This interface (`page.php`) allows you to control the robot's movement direction. The webpage is built with HTML, CSS, and PHP, and connects to a local server using XAMPP for database management.

## Features

- **Directional Control**: Click the buttons to send a command to the robot.
  - **Forward**: Sends a POST request to `F.php`
  - **Backward**: Sends a POST request to `B.php`
  - **Left**: Sends a POST request to `L.php`
  - **Right**: Sends a POST request to `R.php`
  - **Stop**: Sends a POST request to `S.php`

## How It Works

1. **Button Click**: When a directional button is clicked, a single direction (Forward, Backward, Left, Right, Stop) is sent to the corresponding PHP file.
2. **POST Request**: The direction is sent as a POST request to the respective file (`F.php`, `B.php`, `L.php`, `R.php`, `S.php`).
3. **Data Handling**: The PHP file echoes the direction and stores it in the database for further processing.

## Implemented using 🛠️

- **HTML**: Structure of the webpage.
- **CSS**: Styling of the webpage.
- **PHP**: Server-side scripting and handling POST requests.
- **XAMPP**: Local server and database management.

## Files

- `page.php`: Main interface for controlling the robot.
- `F.php`: Handles Forward direction.
- `B.php`: Handles Backward direction.
- `L.php`: Handles Left direction.
- `R.php`: Handles Right direction.
- `S.php`: Handles Stop command.

---

**About This Repository:**
This repository showcases my projects and assignments completed during the web development and NLP track of my training program at Smart Methods Company.
