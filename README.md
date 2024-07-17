# Standard_calculator

### PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <style>
        body {
    background: linear-gradient(to right, #000046, #1CB5E0);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    font-family: Arial, sans-serif;
}

.calculator {
    background-color: #F3E5AB;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
    width: 320px;
}

.display {
    margin-bottom: 20px;
}

.calc-name {
    font-size: 20px;
    text-align: center;
    font-weight: bold;
    color: #000;
}

.calc-number {
    font-size: 15px;
    text-align: center;
    color: #000;
}

.calc-screen {
    background-color: #FFF;
    padding: 10px;
    font-size: 2em;
    text-align: right;
    border: 1px solid #CCC;
    border-radius: 5px;
    margin-top: 10px;
    height: 50px;
}

.buttons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
}

.btn {
    background-color: #6C3483;
    color: #FFF;
    font-size: 1em;
    border: none;
    border-radius: 5px;
    padding: 15px;
    cursor: pointer;
}

.btn:hover {
    background-color: #512E5F;
}

    </style>
</head>
<body>
    <div class="calculator">
        <div class="display">
            <div class="calc-name">Kanmani U</div>
            <div class="calc-number">212221040070</div>
            <div class="calc-screen" id="screen">0</div>
        </div>
        <div class="buttons">
            <button class="btn" onclick="clearScreen()">AC</button>
            <button class="btn" onclick="deleteLast()">DEL</button>
            <button class="btn" onclick="appendChar('/')">/</button>
            <button class="btn" onclick="appendChar('7')">7</button>
            <button class="btn" onclick="appendChar('8')">8</button>
            <button class="btn" onclick="appendChar('9')">9</button>
            <button class="btn" onclick="appendChar('*')">*</button>
            <button class="btn" onclick="appendChar('4')">4</button>
            <button class="btn" onclick="appendChar('5')">5</button>
            <button class="btn" onclick="appendChar('6')">6</button>
            <button class="btn" onclick="appendChar('-')">-</button>
            <button class="btn" onclick="appendChar('1')">1</button>
            <button class="btn" onclick="appendChar('2')">2</button>
            <button class="btn" onclick="appendChar('3')">3</button>
            <button class="btn" onclick="appendChar('+')">+</button>
            <button class="btn" onclick="appendChar('0')">0</button>
            <button class="btn" onclick="appendChar('.')">.</button>
            <button class="btn" onclick="appendChar('%')">%</button>
            <button class="btn" onclick="calculateResult()">=</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
```
### OUTPUT
![image](https://github.com/user-attachments/assets/3b79897d-79d3-444f-8a19-4ca29016c360)

