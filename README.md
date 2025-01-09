### Html
### 1. Create a web page that displays a table with the following columns: Name, Age, and City. The table should have at least 5 rows of data. 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Table</title>
</head>
<body>
    <table>
        <tr>
            <th>Name</th>
            <th>Age</th>
            <th>City</th>
        </tr>
        <tr>
            <td>Raju</td>
            <td>20</td>
            <td>Jaipur</td>
        </tr>
        <tr>
            <td>Amer</td>
            <td>20</td>
            <td>Churu</td>
        </tr>
        <tr>
            <td>Anju</td>
            <td>21</td>
            <td>Ajmer</td>
        </tr>
        <tr>
            <td>Shubham</td>
            <td>19</td>
            <td>Sikar</td>
        </tr>
        <tr>
            <td>Amit</td>
            <td>21</td>
            <td>Kota</td>
        </tr>
    </table>
</body>
</html>

```
### 2. Design a navigation menu with the following links: Home, About, Contact, and Services. The menu should be responsive and work on different devices. 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Responsive Navigation</title>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        .nav{
            box-sizing: border-box;
            border: 1px solid;
            padding: 1rem;
        }
        .nav ul{
            list-style: none;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        .nav ul li a{
            text-decoration: none;
            color: black;
            padding: 0 5px;
            font-size: 1.2rem;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="nav">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">Services</a></li>
        </ul>
    </div>
</body>
</html>
```
### 3. Create a web page that displays a form with the following fields: First Name, Last Name, Email, and Phone Number. The form should have validation to ensure that all fields are filled in correctly. 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
        <form>
            <label for="firstName">First Name :</label>
            <input type="text" name="fName"><br>
            
            <label for="lastName">Last Name : </label>
            <input type="text" name="lName"><br>
            
            <label for="email">Email Add : </label>
            <input type="email" name="email"><br>
            
            <label for="phNum">First Name : </label>
            <input type="number" name="phNum"><br>
            
        </form>
</body>
</html>
```
### 4. Create a web page that displays a list of 10 items, with each item having a checkbox and a delete button. When the delete button is clicked, the item should be removed from the list. 
```html
<!-- Create a web page that displays a list of 10 items, with each item having a checkbox and a delete 
button. When the delete button is clicked, the item should be removed from the list.  -->
<!DOCTYPE html>
<html lang="en">
<head>
    <title>List of Items</title>
</head>
<body>
    <div class="list">
        <input type="checkbox" name="checkbox">
        <span>List-1</span>
        <button class="dlt">Delete</button>
    </div>
    <div class="list">
        <input type="checkbox" name="checkbox">
        <span>List-2</span>
        <button class="dlt">Delete</button>
    </div>
    <div class="list">
        <input type="checkbox" name="checkbox">
        <span>List-3</span>
        <button class="dlt">Delete</button>
    </div>
    <div class="list">
        <input type="checkbox" name="checkbox">
        <span>List-4</span>
        <button class="dlt">Delete</button>
    </div>
    <div class="list">
        <input type="checkbox" name="checkbox">
        <span>List-5</span>
        <button class="dlt">Delete</button>
    </div>
    <div class="list">
        <input type="checkbox" name="checkbox">
        <span>List-6</span>
        <button class="dlt">Delete</button>
    </div>
    <div class="list">
        <input type="checkbox" name="checkbox">
        <span>List-7</span>
        <button class="dlt">Delete</button>
    </div>
    <div class="list">
        <input type="checkbox" name="checkbox">
        <span>List-8</span>
        <button class="dlt">Delete</button>
    </div>
    <div class="list">
        <input type="checkbox" name="checkbox">
        <span>List-9</span>
        <button class="dlt">Delete</button>
    </div>
    <div class="list">
        <input type="checkbox" name="checkbox">
        <span>List-10</span>
        <button class="dlt">Delete</button>
    </div>
    
    <script>
        const lists = document.querySelectorAll(".dlt");
        lists.forEach((item)=>{
            item.addEventListener("click",(event)=>{
                event.target.parentElement.remove();
            })
        })
    </script>
</body>
</html>
```
### 5. Create a web page that displays a calendar with the current month and year. The calendar should have links to navigate to previous and next months. 
```html
abhi nhi kiya
```

# CSS
### 1. Style the table from the HTML assignment question 1 to make it look visually appealing. Use different colors, fonts, and borders to make the table stand out. 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Table</title>
    <style>
        body{
            font-family:sans-serif;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
    table,th,td{
        border: 1px solid;
        
    }
    th,td{
        background-color: pink;
        padding: .5rem;
        text-align: center;
        width: 20vw;
    }
    
    table{
        background-color: orange;
    }
    </style>
</head>
<body>
    <table>
        <tr>
            <th>Name</th>
            <th>Age</th>
            <th>City</th>
        </tr>
        <tr>
            <td>Raju</td>
            <td>20</td>
            <td>Jaipur</td>
        </tr>
        <tr>
            <td>Amer</td>
            <td>20</td>
            <td>Churu</td>
        </tr>
        <tr>
            <td>Anju</td>
            <td>21</td>
            <td>Ajmer</td>
        </tr>
        <tr>
            <td>Shubham</td>
            <td>19</td>
            <td>Sikar</td>
        </tr>
        <tr>
            <td>Amit</td>
            <td>21</td>
            <td>Kota</td>
        </tr>
    </table>
</body>
</html>
```
### 2. Create a CSS layout that includes a header, footer, and main content area. The layout should be responsive and work on different devices. 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Responsive CSS Layout</title>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        .flex{
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        header{
            background-color: orange;
            height: 10vh;
        }
        .mainArea{
            background-color: darkred;
            height: 80vh;
            color: white;
        }
        footer{
            background-color: blue;
            height: 10vh;
            color: white;
        }
    </style>
</head>
<body>
    <header class="flex">
        <h1>Header</h1>
    </header>
    <div class="mainArea flex">
        <h1>Main Content Area</h1>
    </div>
    <footer class="flex">
        <h1>Footer</h1>
    </footer>
</body>
</html>
```
### 3. Style the navigation menu from the HTML assignment question 2 to make it look modern and sleek. Use different colors, fonts, and hover effects to make the menu stand out. 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Nav Bar with CSS</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            font-family: sans-serif;
        }
        .nav{
            box-sizing: border-box;
            box-shadow: 0 0 1rem;
            padding: 1rem;
        }
        ul{
            list-style: none;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        a{
            text-decoration: none;
            color: black;
            padding: 0 5px;
            font-size: 1.2rem;
            font-weight: bold;
            padding: .5rem;
            border-radius: 5px;
        }
        a:hover{
            background-color: chocolate;
            color: white;
        }
    </style>
</head>
<body>
    <div class="nav">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">Services</a></li>
        </ul>
    </div>
</body>
</html>
```
### 4. Create a CSS animation that makes a div element move from one side of the screen to the other. The animation should be smooth and take 2 seconds to complete. 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0; 
        }
        body{
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .box{
            height: 100px;
            width: 100px;
            background-color: red;
            animation: move;
            animation-duration: 2s;
            animation-delay: 1s;
            box-sizing: border-box;
            position: absolute;
            animation-fill-mode: forwards;
        }

        @keyframes move {
            from{
                left: 0;
            }
            to{
                left: 90%;
            }
        }
    </style>
</head>
<body>
    <div class="box">

    </div>
</body>
</html>
```
### 5. Style the form from the HTML assignment question 3 to make it look visually appealing. Use different colors, fonts, and borders to make the form stand out.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            font-family: sans-serif;
        }
        body{
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .box{
            padding: 2rem;
            width: fit-content;
            border-radius: 1rem;
            box-shadow: 0 0 .3rem;
        }
        form{
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 1rem;
            flex-direction: column;
        }
        input{
            width: 50vw;
            font-size: 1.3rem;
            border-radius: .5rem;
            padding: 1rem;
            border: none;
            box-shadow: 0 0 .3rem;
            text-align: center;
            
        }
    </style>
</head>
<body>
    <div class="box">
        <form action="">
            <h1>Fill The Form</h1>
            <input type="text" placeholder="Enter First Name">
            <input type="text" placeholder="Enter First Name">
            <input type="text" placeholder="Enter First Name">
            <input type="text" placeholder="Enter First Name">
        </form>
    </div>
</body>
</html>
```

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
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Form with Validation</title>
  </head>
  <body>
    <form name="myForm" onsubmit="return validateForm()">
      <label for="firstName">First Name:</label>
      <input type="text" id="fName" name="firstName"><br><br>
      <label for="name">Last Name:</label>
      <input type="text" id="lName" name="lastName"><br><br>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email"><br><br>
      <label for="phone">Phone:</label>
      <input type="text" id="phone" name="phone"><br><br>
      <button type="submit">Submit</button>
    </form>
    <script>
      function validateForm() {
        const fName = document.getElementById("fName").value.trim();
        const lName = document.getElementById("lName").value.trim();
        const email = document.getElementById("email").value.trim();
        const phone = document.getElementById("phone").value.trim();

        if (!fName || !lName || !email || !phone) {
          alert("All fields are required.");
          return false;
        }
        if (phone.length !== 10 || isNaN(phone)) {
          alert("Please enter a valid 10-digit phone number.");
          return false;
        }

        alert("Form submitted successfully!");
        return true;
      }
    </script>
  </body>
</html>

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
