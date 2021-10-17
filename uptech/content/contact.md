---
date: 2021-02-12T20:24:31+01:00
draft: false
---

<style>
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  color: #48d1cc;
  border: 1px solid #202020;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
  background-color: #57585a;
  font-size: 20px;
  
}

input[type=submit] {
  background-color: #5e5f60;
  color: #fafafa;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #48d1cc;
}

.container {
  width: 80%;
  border-radius: 5px;
  background-color: #202020;
  padding: 18px;
  color: #fafafa;
  float:center;
  margin: 0 auto;
  
}

@media only screen and (max-width: 600px) {

    .container {

        width: 100%;
    }
}

</style>

<br/>
<br/>
<br/>
<br/>
<br/>

<div align="center">
<h2>Contact Us</h2>
</div>

<div class="container">
  <form name="contact" method="POST" data-netlify="true">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">
    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">
    <label for="email">Email</label>
    <input type="text" id="email" name="email" placeholder="Your email..">
<label for="subject">Subject</label>
<textarea id="subject" name="subject" placeholder="What would you like to share with us.." style="height:200px"></textarea>

<input type="submit" value="Submit">

</form>
</div>

<br/>
<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>
