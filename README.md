<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guide Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #dcbc06;
            position: relative;
        }
        .container {
            text-align: center;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        button {
            background-color: #007BFF;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
        .support-box {
            position: absolute;
            top: 20px;
            left: 20px;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 200px;
            text-align: center;
        }
        .support-box button {
            background-color: #F6A800; /* KO-FI orange */
        }
        .support-box button:hover {
            background-color: #d88f00;
        }
    </style>
</head>
<body>

    <!-- KO-FI Support Box (Top-left corner) -->
    <div class="support-box">
        <h3>Support us at KO-FI</h3>
        <a href="https://ko-fi.com/" target="_blank">
            <button>Support</button>
        </a>
    </div>

    <!-- Main Container (Centered) -->
    <div class="container">
        <h1>You should check out our guide!</h1>
        <a href="https://switchtolinux4.wordpress.com/" target="_blank">
            <button>SWITCH TO LINUX GUIDE</button>
        </a>
    </div>

</body>
</html>
