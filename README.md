# HTML_Form
<html>
    <head>
        <title>Learning Form</title>
    </head>
    <body>
        <form action="https://www.google.com" target="_blank">
            <div class="form-element">
                <label for="firstname">Enter First name: </label>
                <input type="text" name="firstname" class="firstname" />

            </div>
            <br>
            <div class="form-element">
                <label for="lastname">Enter the last name: </label>
                <input type="text" name="lastname" class="lastname" />

            </div>
            <br>
            <div class="form-element">
                <label for="number">Enter the age: </label>
                <input type="number" name="age" class="age"/>
</div>
<br>
<div class="form-element">
    <label for="number">Enter the Password: </label>
    <input type="number" name="password" class="password"/>
</div>
<br>
<div class="form-element">
    <label for="dob">Enter Birth date</label>
    <input type="date" name="dob" class="dob"/>

</div>
<div class="form-element">
    <label for="male"></label> Male</label>
    <input type="radio" name="gender" value="male"/>
    <label for="female">Female: </label>
    <input type="radio" name="gender" value="female"/>
    <label for="na"> does not prefer to say</label>
    <input type="radio" name="gender" value="na"/>
</div>
<div class="checkbox" name="cars" value="BMW">
    <label for="bmw">BMW</label>
    <input type="checkbox" name="cars" value="bmw"/>
    <label for="audi">Audi</label>
    <input type="checkbox" name="cars" value="audi"/> 
</div>
<br>
<input type="file"/>
<br>
<br>
<input type="range" min="0" max="100"/>
<br>
<br>
<input type="submit" />
           </form>
    </body>
</html>
