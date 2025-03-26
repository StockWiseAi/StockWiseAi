<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StockWise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>StockWise: Learn About Stocks</h1>
        <div id="chat-container">
            <div id="chat-box"></div>
            <input type="text" id="user-input" placeholder="Ask me about stocks...">
            <button id="send-btn">Send</button>
        </div>
        <div id="disclaimer">
            <p>Disclaimer: This app does not provide financial advice. Please conduct your own research.</p>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 20px;
}

.container {
    max-width: 600px;
    margin: auto;
    background: white;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

#chat-container {
    margin-top: 20px;
}

#chat-box {
    height: 300px;
    overflow-y: auto;
    border: 1px solid #ccc;
    padding: 10px;
    margin-bottom: 10px;
}

#user-input {
    width: 80%;
    padding: 10px;
}

#send-btn {
    padding: 10px;
}
