# 1.selector-and-properties

## program:
```
<!DOCTYPE html>
<html>
  <head>
    <title>Hello, World!</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <form class="content">
     <h3 class="header">Login</h3>
     <label for="user-name">username:</label><br>
     <input type="text" id="user-name" name="user-name"required><br>
     <label for="password">Password:</label><br>
     <input type="password" id="check" name="password" required><br>
     <button value="submit">submit</button>
     </form>
  </body>
</html>
body{
  background-color:#f0f0f0;
}
.header{
  text-align:center;
  color:grey;
}
#user-name,#check {
  border:2px solid;
  color:#white;
  
}
input[type="password"],
input[type ="text"]{
  color:blue;
  border-radius:5px;
}
button{
  background-color:#3432f3;
  color:white;
  border:1px solid;
  border-radius:5px;
  margin-top:10px;
}
.content{
  background-color:white;
  border-radius:5px;
  
}
```
# output:
![WhatsApp Image 2024-07-14 at 21 55 37_ba04732c](https://github.com/user-attachments/assets/5dbee95c-dc18-45d2-a4a8-793b3fb65aa0)
