# applicationform
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration</title>
</head>
<img src="logo.png"
    <meta name="viewport" content="width=device-width, initial-scale=1">  
<style>  
body{
  background-color: rgb(233, 233, 245);  
}  
.container {  
    padding: 30px;  
  background-color: rgb(23, 240, 15);  
}  
input[type=text], input[type=password], textarea {  
  width: 100%;  
  padding: 10px;  
  margin: 5px 0 20px 0;  
  display: inline-block;  
  border: none;
}  
input[type=text]:focus, input[type=password]:focus {  
  background-color: rgb(248, 247, 244);  
  outline: none;  
}  
 div {  
            padding: 10px 0;  
         }  
hr {  
  border: 1px solid #f1f1f1;  
  margin-bottom: 25px;  
}  
.registerbtn {  
  background-color: #d81010;  
  color: white;  
  padding: 16px 20px;  
  margin: 8px 0;  
  border: none;  
  cursor: pointer;  
  width: 100%;  
  opacity: 0.9;  
}  
</style>  
</head>  
<body>
    <form>  
        <div class="container">  
        <center><h1> Student Application Portal</h1></center>
        <center><h5><i>Please fill out the information below correctly.</i></h5></center>
        <hr>
        <label> Fullname: </label>   
<input type="text" name="Surname first" placeholder= "Start with surname" size="15" required />   
<label> Email Address: </label>   
<input type="text" name="Email address" placeholder= "Email address" size="15" required />   
Contact Address :  
<textarea cols="50" rows="4" placeholder="Current Address" value="address" required>  
</textarea>  

<label> Phone Number: </label>    
<input type="text" name="+234" placeholder="+234-812-345-6789" size="15"required /> 
<label for="Date of Birth">Date of Birth:</label>
<input type="date" id="birthday" name="birthday"> <p>
<label> Upload Passport
    <input type="file" id="myFile" name="filename"> </p>
    </label>
        </div>
    </form> 
    <a href="next.html"><button type="submit" class="registerbtn">Next</button></a>
</body>
</html>
