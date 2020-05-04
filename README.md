# form.html
submitting form
<!DOCTYPE html>
<html>
<style>
<!--#row { float:none;}-->
.col1 {
float: left;
  width: 50%;
  text-align: right;
}
.col2 {
  width: 50%;
  text-align: left;
  float:left;
}
.row { float:none;}
</style>
<body style="background-color:lightblue;">
<header style="text-align:center;">
<h2>Survey Form</h2>
<p>Let us know how we can improve freeCodeCamp</p>
</header>
<div>
<div class="row">
<div class="col1">
  <label for="*Name">First name:</label>
  </div>
  <div class="col2">
  <input type="text" id="fname" name="fname" value="Enter your name">
  </div>
  </div>
  <div class="row">
<div class="col1">
 <label for="email">Enter your email:</label> 
 </div>
  	  <div class="col2">
    <input type="email" id="email" name="email">
  </div>
  </div>
    <div class="row">
<div class="col1">
  <label for="*Age">Age:</label>
  </div>
  	  <div class="col2">
     <input type="number" id="age" name="age" value="Age" min="1" max="100" >
  </div>
  </div>
 <br>
 <div class="row">
  <div class="col1">
  <p>which option suggests your current role?</p>
  </div>
  <div class="col2">
	<select>
  <option value="Student">Student</option>
  <option value="Tranie">Tranie</option>
  <option value="Developer">Developer</option>
  </select>
  </div>
  </div>
  
  <div class="row">
  <div class="col1">
    <p>How likely would you suggest frecodeCamp to your friends?</p>
	</div>
<div class="col2">
  <input type="radio" id="Definitely" name="Definitely" value="">
  <label for="D">Definitely</label><br>
  <input type="radio" id="Maybe" name="Maybe" value="">
  <label for="Maybe">Maybe</label><br>
  <input type="radio" id="Not sure" name="Not sure" value="">
  <label for="Not sure">Not sure</label>
  </div>
  </div>

  <div class="row">
  <div class="col1">
    <p>what do you like the most in fCC:</p>
	</div>
<div class="col2">
  <select>
  <option value="Select a option">Select a option</option>
  <option value="Traning">Tranie</option>
  <option value="staff">Developer</option>
</select> 
 </div>
  </div>

  <div class="row">
  <div class="col1">
     <p>Things that could be improved in the future(check all that apply):</p>
	</div>
	<div class="col2">
 
   <input type="checkbox" id="project type1" name="project type1" value="Front end">
  <label for="project type1"> Front end porjects</label><br>
  <input type="checkbox" id="project type2" name="project type2" value="Back end">
  <label for="project type2"> Back end Projects</label><br>
  <input type="checkbox" id="project type3" name="project type3" value="Boat">
  <label for="project type3"> Data visualization</label>
  </div>
</div>
<br>
<div class="footer" style="text-align: center;">
  	<button class="button">Submit</button>
</div>
</div>
</body>
</html>
