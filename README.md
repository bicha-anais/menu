<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Menu Fast Food</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000000; /* fond noir */
            padding: 30px;
            color: #ffffff; /* texte blanc */
        }
        .menu-container {
            background-color: #1a1a1a;
            border-radius: 15px;
            padding: 20px;
            max-width: 600px;
            margin: auto;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.1);
        }
        h1 {
            text-align: center;
            color: #ffcc00;
        }
        .category {
            margin-top: 20px;
        }
        .category h2 {
            border-bottom: 2px solid #ff9900;
            color: #ffcc00;
        }
        ul {
            list-style-type: none;
            padding-left: 0;
        }
        li {
            display: flex;
            justify-content: space-between;
            padding: 4px 0;
        }
        .title {
            text-align: center;
            font-style: italic;
            margin-bottom: 20px;
        }
        .title span:first-child {
            font-size: 32px;
            color: #ffcc00;
        }
        .title span:last-child {
            font-size: 24px;
            color: #ff9900;
        }
    </style
</head>
<body>

    <!-- Titre personnalisé Fast Food -->
    <div class="title">
        <span>GoMyCode</span><br>
        <span>Fast Food</span>
    </div>

    <div class="menu-container">
        <h1>Menu Fast Food</h1>

        <div class="category">
            <h2>Burgers</h2>
            <ul>
            
                <li><span>Cheeseburger</span><span>300 DA</span></li>
                <li><span>Double Burger</span><span>400 DA</span></li>
                <li><span>Chicken Burger</span><span>350 DA</span></li>
                <li><span>Vegan Burger</span><span>500 DA</span></li>
            </ul>
        </div>

        <div class="category">
            <h2>Snacks</h2>
            <ul>
                
                <li><span>Frites</span><span>150 DA</span></li>
                <li><span>Nuggets (6 pcs)</span><span>250 DA</span></li>
                <li><span>Hot-dog</span><span>300 DA</span></li>
            </ul>
        </div>

        <div class="category">
            <h2>Boissons</h2>
            <ul>
                
                <li><span>Soda</span><span>100 DA</span></li>
                <li><span>Milkshake Vanille</span><span>250 DA</span></li>
                <li><span>Milkshake Chocolat</span><span>250 DA</span></li>
                <li><span>Smoothie Fraise</span><span>300 DA</span></li>
            </ul>
        </div>
    </div>
</body>
</html>
