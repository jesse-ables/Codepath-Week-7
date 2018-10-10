# Codepath-Week-7
Write up of vulnerabilities found in WordPress

Exploit 1 - XSS Using Posts and Comments
An admin or user can input a <script> tag into a post or comment for a post. 
  Step 1: User finds a post created by an admin
  Step 2: User replies to the post
  Step 3: Create a script in the text box
  Step 4: Submit, and let anyone how goes to the site activate the script
  
  
  <img src="https://github.com/jesse-ables/Codepath-Week-7/blob/master/XSSvulnerability.gif" width="800">
