<!DOCTYPE html>
<html>
    <head>
        <title>New Student</title>
     </head>
     <body>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" value="" required placeholder="Type your name here">
        <br>
        <br>
        <label>Date of Birth:</label>
        <input type="date" id="Date of Birth" name="Date of Birth">
        <br>
        <br>
        <label>Gender:</label><br>
        <input type="checkbox" id="male" name="Gender" value="male" required>
        <label>Male</label>
        <input type="checkbox" id="female" name="Gender" value="female" required>
        <label>Female</label><br>
        <br>
        <label>Address:</label>
        <input type="text" id="Address" name="Address" value="" width="350"><br>
        <br>
        <label>Telephone:</label>
        <input type="text" id="Telephone" name="Telephone" value="Country code eg.+254..." required><br>
        <br>
        <label>Email:</label>
        <input type="text" id="Email" name="Email" value="" required placeholder="@gmail.com"><br>
        <br>
        <label>Course: </label>
        <select>
          <option value="Commerce">Commerce</option> 
          <option value="Medicine">Medicine</option> 
          <option value="Engineering">Engineering</option>
          <option value="Pharmacy">Pharmacy</option>
        </select>
        <br> 
        <br>
        <br>
        <button type="submit">Submit</button>
        <button type="cancel">Cancel</button>
     </body>
</html>
