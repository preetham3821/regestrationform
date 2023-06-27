<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <form>
        
        <h1 style="text-align:center">student  application form</h1>
    
        <br>name:<input type="text">
        <br>
        <br>age:<input type="number">
            <div>
            Gender: male<input type="radio" value="male" >
              female<input type="radio" value="female"><br>
              date of birth:
              <input type="date"><br><br>
             
            </div>
            <label>course:</label>
            <select>
                <option value="course">course</option>
                <option value="ai">ai</option>
                <option value="aiml">aiml</option>
                <option value="cse">cse</option>
                <option value="eee">eee</option>
                <option value="bba">bba</option>
                <option value="mba">mba</option>
                <option value="ece">ece</option>
            </select>
        <br><br>
        
        Email:
        <input type="email" id="email" name="email"/> <br>
        <br> <br>
Password:  
<input type="Password" id="pass" name="pass"> <br>   
<br> <br> 
Hobbies:
</label>  
<br>  
<input type="checkbox" name="binge watching"> binge watching <br>  
<input type="checkbox" name="sports"> sports <br>  
<input type="checkbox" name="travelling"> travelling <br>
<input type="checkbox" name="reading Novel"> Reading Novel  <br>
<br>  
<br>
Phone :  
</label>  
<input type="text" name="country code"  value="+91" size="2"/>   
<input type="text" name="phone" size="10"/> <br> <br>   
        
Address:  
<br>  
<textarea cols="80" rows="5" value="address">  
</textarea>  
<br> <br>
<input type="button" value="Submit"/>  
    </form>
</body>
</html>
