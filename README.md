<!DOCTYPE html>
<html>
<head>
    <title>Online Food Page</title>

    <style>
        body {
            font-family: Arial;
            background-color: #fff3e0;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: orange;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .food-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        .food-card {
            background-color: white;
            width: 220px;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0px 0px 10px gray;
        }

        .food-card img {
            width: 100%;
            height: 150px;
            border-radius: 10px;
        }

        button {
            background-color: orange;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: darkorange;
        }
    </style>
</head>

<body>

    <header>
        <h1>Online Food Order</h1>
        <p>Delicious Food Delivered Fast</p>
    </header>

    <div class="food-container">

        <div class="food-card">
            <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd" alt="Burger">
            <h2>Burger</h2>
            <p>Price: ₹120</p>
            <button>Order Now</button>
        </div>

        <div class="food-card">
            <img src="https://images.unsplash.com/photo-1594007654729-407eedc4be65" alt="Pizza">
            <h2>Pizza</h2>
            <p>Price: ₹250</p>
            <button>Order Now</button>
        </div>

        <div class="food-card">
            <img src="https://images.unsplash.com/photo-1604908176997-4310b9c3b4d4" alt="Pasta">
            <h2>Pasta</h2>
            <p>Price: ₹180</p>
            <button>Order Now</button>
        </div>

    </div>

</body>
</html>
