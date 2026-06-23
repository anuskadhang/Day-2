html
<form action="/action.php" method="post">


* Tag:  <form>
* Attributes:   action , method
* Function:  Creates a form. " action" specifies where data is sent, method="post" sends data securely.

html
<label for="username">Username:</label>

* Tag: <label>
* Attribute:  for
* Function: Creates a label for the username field.

html
<input type="text" id="username" name="username">


* Tag: <input>
* Attributes: type ,  id ,  name
* Function:  Creates a text box for entering a username.


html
<br>

* Tag: <br>
* Function:  Inserts a line break.



html
<input type="password" name="password" placeholder="Enter Password">


* Tag: <input>
* Attributes: type ,  name ,  placeholder
* Function:  Creates a password field. Characters are hidden.



html
<input type="checkbox" name="subscribe" value="yes">


* Tag: <input>
* Attributes: type ,  name ,  value
* Function:  Creates a checkbox for subscription.



html
<input type="radio" name="gender" value="male">


* Tag: <input>
* Attributes: type ,  name ,  value 
* Function:  Creates a radio button for Male.



html
<input type="radio" name="gender" value="female">


* Tag: <input>
* Attributes: type ,  name ,  value
* Function: Creates a radio button for Female.



html
<select name="country">


* Tag: <select>
* Attribute: name
* Function: Creates a dropdown list.

---

  html
<option value="us">USA</option>


* Tag: <option>`
* Attribute: value
* Function:  Adds USA as a dropdown option.



  html
<option value="ca">Canada</option>


* Tag: <option>`
* Attribute: value
* Function: Adds Canada as a dropdown option.



  html
<textarea name="comments" rows="4" cols="30"></textarea>


* Tag: <textarea>
* Attributes: name, rows, cols
* Function:  Creates a multi-line text area.



  html
<input type="file" name="resume">


* Tag: <input>
* Attributes: type , name
* Function:  Allows file upload.



  html
<input type="number" name="age" min="18" max="100">


* Tag: <input>
* Attributes: type, name, min, max
* Function: Accepts only numbers between 18 and 100.



  html
<input type="range" name="volume" min="0" max="100">


* Tag: <input>`
* Attributes: type ,  name, min, max
* Function: Creates a slider from 0 to 100.



html
<input type="date" name="dob">


* Tag: <input>
* Attributes: type ,  name
* Function: Opens a date picker.

 

  html
<input type="email" name="email">


* Tag: <input>
* Attributes: type ,  name 
* Function:  Accepts only valid email addresses.



 html
<input type="url" name="website">

* Tag: <input>
* Attributes: type ,  name
* Function:  Accepts website URLs.



  html
<input type="search" name="query">


* Tag: <input>
* Attributes: type ,  name
* Function: Creates a search box.



  html
<button type="submit">Submit</button>


* Tag: <button>`
* Attribute: type`
* Function: Submits the form data.



html
</form>


* Tag: </form>
* Function: Closes the form.
