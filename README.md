
    <style>
        /* Global styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #00000;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 350px;
            margin: 50px auto;
            background-color: white;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            font-size: 36px;
            margin-bottom: 20px;
            font-weight: normal;
        }

        .logo {
            display: block;
            width: 120px;
            margin: 0 auto 20px;
        }

        .input-field {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #dbdbdb;
            border-radius: 5px;
            font-size: 16px;
        }

        .login-btn {
            width: 100%;
            padding: 12px;
            background-color: #3897f0;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            margin: 10px 0;
        }

        .login-btn:hover {
            background-color: #3184d6;
        }

        .forgot-password {
            text-align: center;
            font-size: 14px;
            margin: 10px 0;
        }

        .signup-link {
            text-align: center;
            font-size: 14px;
            color: #3897f0;
        }

        .signup-link a {
            text-decoration: none;
            color: inherit;
        }

        /* Responsive Design */
        @media (max-width: 400px) {
            .container {
                width: 100%;
                padding: 20px;
            }

            h1 {
                font-size: 28px;
            }
        }
    </style>
</head>
<body>


        <h1>Univurse</h1>
        <!-- Login Form -->
        <form action="welcome.html" method="POST" onsubmit="return validateForm()">
            <input type="text" class="input-field" placeholder="Phone number, username, or email" name="username" id="username" required>
            <input type="password" class="input-field" placeholder="Password" name="password" id="password" required>
            <button type="submit" class="login-btn">Log In</button>
        </form>

        <!-- Forgot Password and Sign Up links -->
        <div class="forgot-password">
            <a href="#">Forgot password?</a>
        </div>

        <div class="signup-link">
            Don't have an account? <a href="#">Sign up</a>
        </div>
    </div>

    <script>
        function validateForm() {
            var username = document.getElementById("username").value;
            var password = document.getElementById("password").value;

            if (username == "" || password == "") {
                alert("Both username and password are required.");
                return false; // Prevent form submission
            }
            return true; // Allow form submission
        }
    </script>
</body>
</html>
