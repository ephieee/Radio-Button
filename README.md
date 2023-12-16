# Radio-Button

<input>
type="radio"
Radio buttons allow users to pick just one of a number of options.
name
The name attribute is sent to the server with the value of the option the user selects. When a question provides users with options for answers in the form of radio buttons, the value of the name attribute should be the same for all of the radio buttons used to answer that question.
value
The value attribute indicates the value that is sent to the server for the selected option. The value of each of the buttons in a group should be different (so that the server knows which option the user has selected).
checked
The checked attribute can be used to indicate which value (if any) should be selected when the page loads. The value of this attribute is checked. Only one radio button in a group should use this attribute.


<form action="http://www.example.com/profile.php">
 <p>Please select your favorite genre:
  <br />
  <input type="radio" name="genre" value="rock" checked="checked" /> Rock
  <input type="radio" name="genre" value="pop" /> Pop
  <input type="radio" name="genre" value="jazz" /> Jazz
 </p>
</form>
