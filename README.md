˚ ༘♡ ⋆｡˚˚ ༘♡ ⋆｡˚˚ ༘♡ ⋆｡˚

**About This Repository:**
This repository showcases my projects and assignments completed during the web development and NLP track of my training program at Smart Methods Company.

---
# 🤖 Robot Movement Control Interface

This interface (`page.php`) allows you to control the robot's movement direction. The webpage is built with HTML, CSS, and PHP, and connects to a local server using XAMPP for database management.

## 🛠️ Key Functionalities

- **Directional Control**: Click the buttons to send a command to the robot.
  - **⬆️ Forward**: Sends a POST request to `F.php`
  - **⬇️ Backward**: Sends a POST request to `B.php`
  - **⬅️ Left**: Sends a POST request to `L.php`
  - **➡️ Right**: Sends a POST request to `R.php`
  - **⏹️ Stop**: Sends a POST request to `S.php`

## ⚙️ How It Works

1. **Button Click**: When a directional button is clicked, a single direction (Forward, Backward, Left, Right, Stop) is sent to the corresponding PHP file.
2. **POST Request**: The direction is sent as a POST request to the respective file (`F.php`, `B.php`, `L.php`, `R.php`, `S.php`).
3. **Data Handling**: The PHP file echoes the direction and stores it in the database for further processing.


## 📂 Files

- `page.php`: Main interface for controlling the robot.
- `F.php`: Handles Forward direction.
- `B.php`: Handles Backward direction.
- `L.php`: Handles Left direction.
- `R.php`: Handles Right direction.
- `S.php`: Handles Stop command.
## 🎥 Demo Video

Watch the demo video to see the interface in action: [Demo Video]([https://www.example.com/demo-video](https://github.com/shathalshehri/Human-Robot-Controller/blob/main/demo.mov)

## 🧰 Implemented using 

- **HTML**: Structure of the webpage.
- **CSS**: Styling of the webpage.
- **PHP**: Server-side scripting and handling POST requests.
- **XAMPP**: Local server and database management.
- 
## 🛠️ Troubleshooting

If you encounter issues after changing your database password in phpMyAdmin, you might find this resource helpful: [Solved: mysqli_real_connect(): (HY000/1045): Access denied for user 'root'@'localhost' (using password: YES)](https://sahilali.medium.com/solved-mysqli-real-connect-hy000-1045-access-denied-for-user-root-localhost-using-b56a9214d06a).

## 📚 Additional Resources

For setting up and installing XAMPP on a Mac, you might find this video tutorial helpful: [How to Install XAMPP on macOS](https://www.youtube.com/watch?v=ryq01KSn00o).


