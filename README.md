<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorry My Love</title>
    <style>
        body {
            margin: 0;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            background: linear-gradient(135deg, #FFD1DC, #C8E6FF);
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        h1 {
            font-size: 4rem;
            color: #FF69B4;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            animation: bounce 1.5s infinite;
        }

        p {
            font-size: 1.5rem;
            color: #555;
            margin: 20px 0;
        }

        .heart {
            position: relative;
            width: 150px;
            height: 150px;
            background-color: #FF69B4;
            transform: rotate(-45deg);
            animation: pulse 2s infinite;
        }

        .heart::before,
        .heart::after {
            content: '';
            position: absolute;
            width: 150px;
            height: 150px;
            background-color: #FF69B4;
            border-radius: 50%;
        }

        .heart::before {
            top: -75px;
            left: 0;
        }

        .heart::after {
            top: 0;
            left: 75px;
        }

        footer {
            margin-top: 30px;
            font-size: 1rem;
            color: #666;
        }

        footer a {
            color: #FF69B4;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            text-decoration: underline;
        }

        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }

        @keyframes pulse {
            0%, 100% {
                transform: scale(1) rotate(-45deg);
            }
            50% {
                transform: scale(1.1) rotate(-45deg);
            }
        }
    </style>
</head>
<body>
    <h1>Sorry My Love</h1>
    <div class="heart"></div>
    <p>You mean everything to me. Please forgive me. ❤️</p>
    <footer>
        Made with ❤️ for you by <a href="#">someone who truly cares</a>
    </footer>
</body>
</html>
