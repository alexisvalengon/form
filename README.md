<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>My Registration Form</h1>

    <div>
        <label for="first_name">First Name:</label>
        <input type="text" id="first_name" name="first_name">
    </div>
    <div>
        <label for="last_name">Last Name:</label>
        <input type="text" id="last_name" name="last_name">
    <div>
    <div>
        <label for="email">Email:</label>
        <input type="text" id="email" name="email">
        <form>
            <label>
                Password:<input type="password" name="password">
                
            </label>
        </form>
        <form>
            <label>
                Confirm Password:<input type="password" name="confirm password">
                <br><br>Birthday<input type="date" >          
        </label>
    <div>
        <form>  
            <label>
            Male<input type="radio" name="gender" value="male"> 
            </label>
            <label> 
            Female<input type="radio" name="gender" value="female">
            </label>
            <label>
            Other<input type="radio" name="gender" value="decline">
            </label>
        </form>
        <form>
            <Label>
                <p>A short description about yourself.</p>
                <textarea></textarea>
            </Label>  
        </form>
        <form>
                <br><br>Favorite Language
            <select id="Javasacipt">
                    <option value="Java">Java</option>
                    <option value="C++">C++</option>
                    <option value="CSS">CSS</option>
                    <option value="Pyton">Pyton</option>
            </select>


        </form>
        <input type="submit" name="" id="">
</body>
</html>
