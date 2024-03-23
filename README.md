<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Simple Calculator</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
    }
    .calculator {
        width: 300px;
        margin: 50px auto;
        background-color: #fff;
        border: 1px solid #ccc;
        border-radius: 5px;
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    }
    .display {
        width: 100%;
        padding: 10px;
        font-size: 18px;
        text-align: right;
        border: none;
        outline: none;
    }
    .button-row {
        display: flex;
    }
    .button {
        flex: 1;
        padding: 15px;
        font-size: 16px;
        border: none;
        background-color: #f0f0f0;
        cursor: pointer;
        transition: background-color 0.3s ease;
    }
    .button:hover {
        background-color: #e0e0e0;
    }
</style>
</head>
<body>

<div class="calculator">
    <input class="display" type="text" disabled>
    <div class="button-row">
        <button class="button">7</button>
        <button class="button">8</button>
        <button class="button">9</button>
        <button class="button">+</button>
    </div>
    <div class="button-row">
        <button class="button">4</button>
        <button class="button">5</button>
        <button class="button">6</button>
        <button class="button">-</button>
    </div>
    <div class="button-row">
        <button class="button">1</button>
        <button class="button">2</button>
        <button class="button">3</button>
        <button class="button">*</button>
    </div>
    <div class="button-row">
        <button class="button">C</button>
        <button class="button">0</button>
        <button class="button">=</button>
        <button class="button">/</button>
    </div>
</div>

</body>
</html>
