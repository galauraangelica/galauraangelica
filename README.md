<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Pseudo-class Challenge</title>
    <link rel="stylesheet" href="challenge.css">
    <style>
        /* Basic styles for the page */
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
            background-color: #f0f0f0;
        }

        header h1 {
            text-align: center;
            color: #333;
        }

        main {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }

        /* Button styles */
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        button:hover {
            background-color: #4CAF50; /* Change background color on hover */
        }

        button:active {
            font-size: 18px; /* Increase font size when clicked */
            color: #fff; /* Change text color when clicked */
            background-color: #2E7D32; /* Darker shade when clicked */
            transform: scale(1.1); /* Slightly enlarge the button when clicked */
        }

        /* Input styles */
        input[type="text"] {
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc;
            transition: all 0.3s ease;
        }

        input[type="text"]:focus {
            border-color: #4CAF50; /* Add a border when focused */
            color: #000; /* Change text color when typing */
        }

        input[type="text"]::placeholder {
            color: #888;
        }

        input[type="text"]:focus::placeholder {
            color: #666; /* Change placeholder color when focused */
        }

        /* Anchor link styles */
        a {
            color: #1E90FF;
            text-decoration: none;
            transition: all 0.3s ease;
        }

        a:hover {
            color: #104E8B; /* Change text color on hover */
            text-decoration: underline; /* Add underline on hover */
        }

        a:active {
            font-weight: bold; /* Change font weight when clicked */
            color: #08306B; /* Change color when clicked */
            transform: scale(1.1); /* Slightly enlarge the link when clicked */
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the CSS Pseudo-class Challenge!</h1>
    </header>
    <main>
        <button>Click Me!</button>
        <input type="text" placeholder="Enter your name">
        <a href="#">Visit our website</a>
    </main>
</body>
</html>
