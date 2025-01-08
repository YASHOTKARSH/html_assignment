# JavaScript
### 1. Create a JavaScript function that calculates the sum of all the numbers in an array. The function should take an array as input and return the sum.
```javascipt
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Sum Of Array</title>
</head>
<body>
    <script>
        function calculate(){
            const values = prompt("Enter Values with Space example:(1 2 3)");
            let sum=0;
            const arr = values.split(" ");
            arr.forEach((item)=>{
                sum=sum+parseInt(item);
            })
            return sum;
        }
        const result = calculate();
        alert(`Sum of Array is ${result} `)
    </script>
</body>
</html>
```
### 2. Create a JavaScript function that validates a form to ensure that all fields are filled in correctly. The function should check for empty fields, invalid email addresses, and invalid phone numbers. 
```javascript
abhi nhi kiya
```
### 3. Create a JavaScript function that generates a random number between 1 and 100. The function should return the random number.
```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Random Number Generate</title>
</head>
<body>
    <script>
        function random(){
            const number = (Math.floor(Math.random()*100))+1;
            return number;
        }
        const number = random();
        alert(`Random Number is ${number}`);
    </script>
</body>
</html>
```
### 4. Create a JavaScript function that sorts an array of objects by a specific property. The function should take an array and a property name as input and return the sorted array.
```javascript
abhi nhi kiya
```

### 5. Create a JavaScript function that creates a new element and adds it to the DOM. The function should take the element type, id, and class as input and return the new element.
```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Element Creation</title>
    <style>
        
    </style>
</head>
<body>
    <script>
        function newElement(){
        const element = prompt("Enter Element Name");
        const className = prompt("Enter Class Name");
        const idName = prompt("Enter id Name");
        const createElement = document.createElement(element);
        createElement.setAttribute("class",className)
        createElement.setAttribute("id",idName);
        createElement.innerHTML=`It's ${element} Element`;
        document.body.appendChild(createElement);
        }
        newElement();
    </script>
</body>
</html>
```
