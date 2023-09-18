
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* styles.css */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .login-container {
            background-color: #914343;
            padding: 28px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 300px;
        }

        .login-container h2 {
            color: #333;
        }

        .login-form {
            margin-top: 20px;
        }

        .login-form label {
            display: block;
            text-align: left;
            margin-bottom: 5px;
        }

        .login-form input[type="text"],
        .login-form input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 3px;
        }

        .login-form button {
            background-color: #ff6600;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>Login</h2>
        <form class="login-form" id="login-form">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <br>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <br>
            <button type="submit">Login</button>
        </form>
        <p>Don't have an account? <a href="registration.html">Create Account</a></p>
    </div>

    <script>
        document.getElementById("login-form").addEventListener("submit", function (e) {
            e.preventDefault();

            const username = document.getElementById("username").value;
            const password = document.getElementById("password").value;

            // Replace with your actual login logic
            if (username === "darshan" && password === "7338541530") {
                window.location.href = "index.html"; // Adjust the URL as needed
            } else {
                alert("Invalid username or password. Please try again.");
            }
        });
    </script>
</body>
</html>


