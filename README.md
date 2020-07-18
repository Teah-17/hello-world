<!DOCTYPE html>
<html lang="en">
<h1>Login Page</h1>


<html>
<div>
<form action="/action_page.php" method="post">
	<div class="imgcontainer">
    <img src="https://cdn.pixabay.com/photo/2015/10/05/22/37/blank-profile-picture-973460_1280.png" alt="Display Picture" class="avatar">
    
<button onclick="document.getElementById('id01').style.display='block'">Login?</button>


<div id="id01" class="modal">
  <span onclick="document.getElementById('id01').style.display='none'"
class="close" title="Close Modal">&times;</span>


    <div class="container">
      <label for="uname"><b>Username:</b></label>
      <input type="text" placeholder="Enter Username" name="uname" required>

      <label for="psw"><b>Password:</b></label>
      <input type="password" placeholder="Enter Password" name="psw" required>

      <button type="submit">Login</button>
      <label>
        <input type="checkbox" checked="checked" name="remember"> Remember me
      </label>
    </div>


    <div class="container" style="background-color:#f1f1f1">
      <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>
      <span class="psw">Forgot <a href="#">password?</a></span>
    </div>
    
<style>
.cancelbtn {
  width: auto;
  padding: 10px 18px;
  background-color: #f44336;
 }
 
button {
 	background-color: #4E91F6;
    color: black;
    width: auto;
    padding:10px 18px;
 }
button: hover {
	opacity: 0.8;
 }
img.avatar {
	width: 30%;
    border-radius: 50%;
 }
 
 .imgcontainer {
 	text-align: center;
    margin: 24px 0 12px 0;
}

.container {
	padding: 16px;
}

span.psw {
  float: right;
  padding-top: 16px;
} 
input[type=text], input[type=password] {
  width: 80%;
  padding: 10px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}   

</style>
</form>
</div>
</html>









<form action="action_page.php">
	<div class="container">
    	<h1> Register Here! </h1>
        <p> Fill in the form below to create an account.</p>
        <hr>
        
   <label for="email"><b>Email:</b></label>
        <input type="text" placeholder="Email here"name="email" id="email" required>
        
   <label for="psw"><b>Password:</b></label>
        <input type="password" placeholder="Password Here" name="psw" id="psw" required>
        
   <label for="psw-repeat"><b>Re-Enter Password:</b></label>
        <input type="password" placeholder="Re-enter password Here"name="psw-repeat" id="psw-repeat" required>
        <hr>
        
   <button type="submit" class="registerbtn">Register Now!</button>
       </div>
       
   <div class="container signin">
       	<p> Already have an account? <a href=" https://www.w3schools.com/code/tryit.asp?filename=GGHMYR3ESMC0">Sign in</a>.</p>
       </div>
       
       
   <style> 
       .registerbtn {
       background-color: #59CD62;
       color: black;
       width: 50%;
       padding: 12px 16px;
      }
      a {
      color: blue;
      }
      .container {
      padding:16px;
     }
     input[type=text], input[type=password] {
     width: 100%;
     padding: 16px;
     margin: 5px 0 22px 0;
    }
    </style>
      </form>
