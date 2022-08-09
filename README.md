<html>
<body>
<h2 style="color: blue;">Personal Information</h2>
<form>

    <label for="fname">First Name:</label> 
    <input type="text" value="" id="fname" >
<br>

    <br><label for="lname">Last Name:</label>
    <input type="text" value="" id="lname" >
    <br>
    
    <br><label for="gender">Gender:</label>
    
    <input type="radio" name="gender" id="male"> 
    <label for="male">Male</label>

    
    <input type="radio" name="gender" id="female"> 
    <label for="female">Female</label>
    <br>
    
    <br><label for="pics">Profile Image : </label> 
    <input type="file" id="pics" multiple>
    <br>
    
    <br><label for="textarea">Self-Description:</label>
    <br><textarea rows="4"></textarea><br>
    
    <br><label for="Select Country">Select the Country:</label> 
        <select>
        <option selected disabled>--Select Country--</option>
        <option>India</option>
        <option>Australia</option>
        <option>Bangladesh</option>
        <option>Colombia</option>
        <option>Denmark</option>
        <option>Egypt</option>
        <option>France</option>
        <option>Germany</option>
        <option>Italy</option>
        </select><br>
    
    <br><button type="reset">Reset</button>
   
    <input type="Submit" value="Submit">
</form>

</body>
</html>
