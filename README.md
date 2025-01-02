<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body styling */
        body {
            font-family: Arial, sans-serif;
            background-color: black;  /* Black background */
            color: white;  /* White text color */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
        }

        /* Login container */
        .login-container {
            width: 350px;
            padding: 30px;
            background-color: white;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            text-align: center;
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

        /* Hover effect for the login button */
        button:hover {
            background-color: green;  /* Change background to green on hover */
        }

        /* Forgot Password Box */
        .forgot-password-box {
            margin-top: 10px;
            padding: 10px;
            background-color: #f1f1f1;
            border-radius: 5px;
            border: 1px solid #dbdbdb;
            text-align: center;
        }

        /* Forgot password style */
        .forgot-password {
            color: grey;
            font-size: 14px;
            text-decoration: none;
        }

        .forgot-password:hover {
            color: red;
            text-decoration: underline;
        }

        /* Footer link styles */
        .footer {
            margin-top: 20px;
        }

        .footer a {
            font-size: 12px;
            color: #8e8e8e;
            text-decoration: none;
        }

        .footer a:hover {
            color: red;
            text-decoration: underline;
        }

        /* Download Now Button */
        .download-btn {
            padding: 8px 20px;
            background-color: #0095f6;
            color: black;
            text-decoration: none;
            border-radius: 50px;
            font-size: 12px;
            text-align: center;
            margin-right: 20px;
        }

        .download-btn:hover {
            background-color: green;
            color: white;
        }

        /* QR Content Positioning */
        .qr-content {
            position: absolute;
            left: 5%;
            top: 80%;
            transform: translateY(-50%);
            text-align: left;
            padding-left: 20px;
        }

        .login-with-qr {
            font-size: 18px;
            font-weight: bold;
            color: white;
            text-decoration: none;
            margin-bottom: 10px;
        }

        .login-description {
            font-size: 14px;
            color: white;
        }

        /* Responsive Design */
        @media (max-width: 400px) {
            .login-container {
                width: 90%;
            }
        }
    </style>
</head>
<body>
    <!-- Header with the Logo -->
    <div style="font-size: 50px; font-weight: bold; text-align: center; text-decoration: underline;">
        𝔽𝕦𝕤𝕚𝕠𝕟
    </div>

    <!-- Login Container -->
    <div class="login-container">
        <form action="/submit" method="post">
            <input type="text" name="username" placeholder="Phone, email, or username" required>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit">Log in</button>
        </form>

        <!-- Forgot Password Box -->
        <div class="forgot-password-box">
            <a href="password-reset.html" class="forgot-password">Forgot password?</a>
        </div>

        <!-- Footer with Register link -->
        <div class="footer">
            <a href="https://www.example.com/register">Need an account? Register</a>
        </div>
    </div>

    <!-- QR Content Section for Login -->
    <div class="qr-content">
        <a href="#" class="login-with-qr">Log in with QR Code</a>
        <div class="login-description">Scan this with the mobile app to log in instantly.</div>
    </div>

    <!-- Top Border and Download Now Button -->
    <div class="top-border">
        <a href="https://www.example.com/download" class="download-btn">Download Now</a>
    </div>

    <!-- Bottom Border -->
    <div class="bottom-border">
        <a href="#">Footer Content</a>
    </div>
</body>
</html>



