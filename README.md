# calculator
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Calculator</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .calculator {
            display: inline-block;
            margin: 20px;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="calculator">
        <h2>Calculator</h2>
        <input type="text" id="result" readonly>
        <br><br>
        <button onclick="clearResult()">C</button>
        <button onclick="appendToResult('1')">1</button>
        <button onclick="appendToResult('2')">2</button>
        <button onclick="appendToResult('+')">+</button>
        <br>
        <button onclick="appendToResult('3')">3</button>
        <button onclick="appendToResult('4')">4</button>
        <button onclick="appendToResult('5')">5</button>
        <button onclick="appendToResult('6')">6</button>
        <button onclick="appendToResult('7')">7</button>
<button onclick="appendToResult('8')">8</button>
<button onclick="appendToResult('9')">9</button>
<button onclick="appendToResult('0')">0</button>
        <button onclick="appendToResult('-')">-</button>
        <br>
        <button onclick="calculateResult()">=</button>
    </div>
