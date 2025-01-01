<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - Instagram</title>
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
            background-color: black; /* Black background */
            color: white; /* White text */
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

        /* Logo */
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

        /* Button */
        button {
            width: 100%;
            padding: 10px;
            background-color: #0095f6; /* Instagram blue */
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 14px;
            cursor: pointer;
        }

        button:hover {
            background-color: green; /* Hover effect */
        }

        /* Forgot password link */
        .forgot-password-box {
            margin-top: 10px;
            padding: 10px;
            background-color: #f1f1f1;
            border-radius: 5px;
            border: 1px solid #dbdbdb;
            text-align: center;
        }

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

        /* Download button */
        .download-btn {
            padding: 8px 20px;
            background-color: #0095f6; /* Blue background */
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

        /* QR Code content */
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

        /* Borders */
        .top-border, .bottom-border {
            position: fixed;
            width: 100%;
            background-color: black;
            border-top: 5px solid grey;
            padding: 10px 0;
            text-align: right;
        }

        .bottom-border {
            bottom: 0;
            text-align: center;
        }
    </style>
</head>
<body>

    <!-- Top Border with Download Button -->
    <div class="top-border">
        <a href="https://www.example.com/download" class="download-btn">Download Now</a>
    </div>

    <!-- Login Container -->
    <div class="login-container">
        <div class="logo">
            <!-- Instagram logo here -->
        </div>
        <form action=
