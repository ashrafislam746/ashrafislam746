<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free Fire Diamond Top-Up</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .top-up-form {
            max-width: 500px;
            margin: 40px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .top-up-form h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .top-up-form input, .top-up-form select {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .top-up-form button {
            background-color: #ff5500;
            color: white;
            padding: 15px;
            width: 100%;
            border: none;
            cursor: pointer;
            border-radius: 4px;
        }
        .top-up-form button:hover {
            background-color: #e64a00;
        }
        .payment-info {
            margin-top: 20px;
            text-align: center;
            color: #555;
        }
        .payment-info p {
            margin: 10px 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Free Fire Diamond Top-Up</h1>
    <p>Enter your details to top-up your Free Fire account</p>
</header>

<div class="top-up-form">
    <h2>Top-Up Your Account</h2>
    <form>
        <label for="player-id">Free Fire Player ID</label>
        <input type="text" id="player-id" name="player-id" placeholder="Enter your Free Fire ID" required>

        <label for="diamond-amount">Select Diamond Amount</label>
        <select id="diamond-amount" name="diamond-amount" required>
            <option value="100">100 Diamonds - $1</option>
            <option value="500">500 Diamonds - $5</option>
            <option value="1000">1000 Diamonds - $10</option>
        </select>

        <button type="submit">Top-Up Now</button>
    </form>

    <div class="payment-info">
        <p>Send Payment via Bkash to: <strong>01621749783</strong></p>
        <p>After payment, please confirm your transaction ID.</p>
    </div>
</div>

<footer>
    <p>&copy; 2024 Free Fire Top-Up Service. All Rights Reserved.</p>
</footer>

</body>
</html>
