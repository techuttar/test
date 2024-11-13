<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Landing Page with Ads</title>
    <style>
        /* Reset CSS */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body styling */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f8f9fa;
            display: flex;
            flex-direction: column;
            align-items: center;
            color: #333;
        }

        /* Header styling */
        header {
            width: 100%;
            background-color: #3498db;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Scrolling Text Section */
        .scrolling-text {
            width: 100%;
            background-color: #2980b9;
            color: #fff;
            padding: 10px 0;
            white-space: nowrap;
            overflow: hidden;
            text-align: center;
            font-size: 18px;
            font-weight: bold;
            box-sizing: border-box;
        }

        .scrolling-text p {
            display: inline-block;
            padding-left: 100%;
            animation: scrollText 20s linear infinite; /* Changed speed to 20s */
        }

        /* Scroll Text Animation (Without smooth animation) */
        @keyframes scrollText {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }

        /* Main container styling */
        .container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            max-width: 900px;
            padding: 40px;
            margin: auto;
        }

        /* Image Card Styling */
        .image-card {
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            padding: 20px;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        /* Card Hover Effect */
        .image-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }

        .image-card img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }

        /* Enhanced Blue Button Styling */
        .button-container {
            display: flex;
            gap: 30px;
            justify-content: center;
            margin-top: 20px;
        }

        .button-container a {
            text-decoration: none;
            color: #fff;
            padding: 30px 70px; /* Increased padding for larger buttons */
            font-size: 24px; /* Larger font size */
            font-weight: bold;
            border-radius: 30px;
            background: linear-gradient(45deg, #4e73df, #1e3a8a); /* Blue gradient background */
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        /* Button Hover Effect */
        .button-container a:hover {
            transform: scale(1.1); /* Slightly enlarge button on hover */
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
        }

        /* Ad Section Styling */
        .ad-container {
            width: 100%;
            max-width: 900px;
            margin: 20px auto;
            text-align: center;
            padding: 20px;
            background-color: #ecf0f1;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .ad-container iframe {
            width: 100%;
            height: 250px; /* You can adjust the height as needed */
            border: none;
            border-radius: 8px;
        }

        /* Footer styling */
        footer {
            width: 100%;
            background-color: #3498db;
            color: #fff;
            text-align: center;
            padding: 15px 0;
            font-size: 14px;
        }

        /* Responsive Styles */
        @media (max-width: 768px) {
            header {
                font-size: 20px;
            }

            .scrolling-text {
                font-size: 16px;
            }

            .container {
                grid-template-columns: 1fr;
                padding: 20px;
            }

            .button-container a {
                padding: 15px 30px; /* Adjusted size for mobile */
                font-size: 18px; /* Adjusted font size for mobile */
            }
        }

        @media (max-width: 480px) {
            header {
                font-size: 18px;
                padding: 15px 0;
            }

            .scrolling-text {
                font-size: 14px;
            }

            .container {
                grid-template-columns: 1fr;
                padding: 10px;
            }

            .button-container a {
                padding: 12px 25px; /* Adjusted size for smaller screens */
                font-size: 16px; /* Adjusted font size */
            }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>Welcome to Our Responsive Landing Page</header>

    <!-- First Scrolling Text Section -->
    <div class="scrolling-text">
        <p>Welcome to our website! Here you'll find the latest updates, offers, and exciting news! Stay tuned!</p>
    </div>

    <!-- Ad Section below First Scrolling Text -->
    <div class="ad-container">
        <iframe src="https://www.example.com/ad" title="Advertisement"></iframe>
    </div>

    <!-- Main Container with Image Cards -->
    <div class="container">
        <div class="image-card">
            <img src="https://techuttar.sirv.com/Copy%20of%20techuttar.com.png" alt="Image 1">
            <div class="button-container">
                <a href="https://www.profitablecpmrate.com/ehkzrvqp9?key=7160baec0293a83933f4868000ffd0d8">Play HD</a>
                <a href="https://www.profitablecpmrate.com/ehkzrvqp9?key=7160baec0293a83933f4868000ffd0d8">Download</a>
            </div>
        </div>
        <div class="image-card">
            <img src="https://techuttar.sirv.com/how%20to%20make.png" alt="Image 2">
            <div class="button-container">
                <a href="https://www.profitablecpmrate.com/ehkzrvqp9?key=7160baec0293a83933f4868000ffd0d8">Play HD</a>
                <a href="https://www.profitablecpmrate.com/ehkzrvqp9?key=7160baec0293a83933f4868000ffd0d8">Download</a>
            </div>
        </div>
        <div class="image-card">
            <img src="https://techuttar.sirv.com/hydrogen.png" alt="Image 3">
            <div class="button-container">
                <a href="https://www.profitablecpmrate.com/ehkzrvqp9?key=7160baec0293a83933f4868000ffd0d8">Play HD</a>
                <a href="https://www.profitablecpmrate.com/ehkzrvqp9?key=7160baec0293a83933f4868000ffd0d8">Download</a>
            </div>
        </div>
        <div class="image-card">
            <img src="https://techuttar.sirv.com/imresizer-1730626467795.jpg" alt="Image 4">
            <div class="button-container">
                <a href="https://www.profitablecpmrate.com/ehkzrvqp9?key=7160baec0293a83933f4868000ffd0d8">Play HD</a>
                <a href="https://www.profitablecpmrate.com/ehkzrvqp9?key=7160baec0293a83933f4868000ffd0d8">Download</a>
            </div>
        </div>
    </div>

    <!-- Ad Section below Second Scrolling Text -->
    <div class="ad-container">
        <iframe src="https://www.example.com/ad" title="Advertisement"></iframe>
    </div>

    <!-- Footer Section -->
    <footer>
        &copy; 2024 Your Website. All Rights Reserved.
    </footer>

</body>
</html>
