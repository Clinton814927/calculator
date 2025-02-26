<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1 style="position: absolute; z-index: 100; left: 0; top: 0; text-align: center; color: white; width: 100%; font-family: Arial, Helvetica, sans-serif;">EMMA'S CALCULATOR</h1>
    <div id="Calculator">
    <input id="display" readonly placeholder="0"/>
    <div id="Keys">
    <button onClick="appendToDisplay('7')">7</button>
    <button onClick="appendToDisplay('8')">8</button>
    <button onClick="appendToDisplay('9')">9</button>
    <button onClick="clearDisplay()" class="sign">⇚</button>
    <button onClick="appendToDisplay('4')">4</button>
    <button onClick="appendToDisplay('5')">5</button>
    <button onClick="appendToDisplay('6')">6</button>
    <button onClick="appendToDisplay('+')" class="sign">+</button>
    <button onClick="appendToDisplay('1')">1</button>
    <button onClick="appendToDisplay('2')">2</button>
    <button onClick="appendToDisplay('3')">3</button>
    <button onClick="appendToDisplay('-')" class="sign">-</button>
    <button onClick="appendToDisplay('.')" class="sign">.</button>
    <button onClick="appendToDisplay('0')">0</button>
    <button onClick="appendToDisplay('*')" class="sign">x</button>
    <button onClick="appendToDisplay('/')" class="sign">÷</button>    
    <button></button>

    <button onClick="calculate()" class="equal">=</button>
</div>
    </div>
</body>
<script src="index.js"></script>
</html>
