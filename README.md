 Normal Login  Pgae  code
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-color: lightblue;
        }
        .container{
            text-align: center;
            margin-top: 100px;
            background-color: bisque;
            padding: 50px;
            border-radius: 25px;

        }
        .container form{
            font-size: 30px;
            font-weight: bold;
            background-color: white;
            margin: 10px;
            padding: 10px;
            border-radius: 10px;
        }
         
        .container  :hover{
            /* background-color: rgb(167, 35, 35); */
          

        }
        .can{
            border-radius: 10px;
            border-color: blue;
            padding: 10px;
            background-color: white;
        }
          .can :hover{
            border-radius: 10px;
            border-color: blue;
            padding: 10px;
            background-color: white;
          }
        .button  :hover {
            margin: 10px;
            padding: 10px;
            border-radius: 10px;
            background-color: rgb(214, 13, 13);
            color : rgb(2, 2, 2);
            


        }
        .container .button{
            margin: 10px;
        }
    </style>
</head>
<body>
    
    <div class="container">
        <form action="submit">Login your account</form>
        <br>
        <div class="can">
         Enter your username: <input type="text">
         </div>
         <br>
         <div class="can">
         Enter your password: <input type="text">
         </div>
         <br>
         <div class="button">
            <button type = "submit">Login your account

            </button>
            
         </div>
    </div>
    
</body>
</html>
