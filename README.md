<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2> JS functions </h2>
    <button onclick="sayHi()"> Say Hello </button>
    <button onclick="addNumbers()"> Addition </button>
    <button onclick="showTime()"> Time </button>
    <div id="output"></div>
    <script>
        function sayHi() {
            document.getElementById("output").innerText="Hello, how are you?"
        }
        function addNumbers() {
            let a=100,b=200;
            let sum=a+b;
            document.getElementById("output").innerText="Sum of"+a+"+"+b+" = "+sum;
        }
        function showTime(){
            let now=new Date();
            document.getElementById("output").innerText="Current Time"+ now.toLocaleTimeString();
        }
    </script>
</body>
</html>
