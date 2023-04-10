<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Securty</title>
    <style>
        *{
            margin: 2px;
            padding: 0;
            box-sizing: border-box;

        }
        body {
            min-height: 100vh;
            background-color: black;
            display: flex;
            font-family: sans-serif;
        }

        .container {
                margin: auto;
                width: center;
                max-width: 90% ;

        }
        .container form {
              width: 100%;
              height: 100%;
              padding: 20px;
              background: white;
              border-radius: 4px;
              box-shadow: 0 8px 16px rgba(0,0,0,.3);

        }
        .btn {
            margin-top: 10px;
            margin-left: 70px;
            width:50%;
            height: 50%;
            padding: 10px;
            border-radius: 6px;
        }
        .container form .form-control {
             width: 100%;
             height: 40px;
             background: rgb(241, 241, 241);
             border-radius: 10px;
             border: 1px solid silver;
             margin: 10px 10 18px 0;
             padding: 0 10px;

        }
        
       
    </style>

</head>
<body >
       <div class= "container" >
        <form action ="" >
            <h1>Login Form</h1>
            <div class = "form-group">
                <label for= "">Email id </label>
                <input type ="text" class ="form-control" required >

            </div>
            <form action ="" >
                <div class = "form-group1">
                    <label for= "">Password</label>
                    <input type ="text" class ="form-control" required >
    
                </div>
                <input type="submit" class ="btn" value="Login">
                <input type="reset" class ="btn" value="Clear">
               
            </form>
            </form>
    
</body>
</html>
