# Codepath-Week-7
Write up of vulnerabilities found in WordPress

Exploit 1 - XSS Using Posts and Comments
WP Version: 4.2
An admin or user can input a <script> tag into a post or comment for a post. 
  Step 1: User finds a post created by an admin
  Step 2: User replies to the post
  Step 3: Create a script in the text box
  Step 4: Submit, and let anyone how goes to the site activate the script
  
  
  <img src="https://github.com/jesse-ables/Codepath-Week-7/blob/master/XSSvulnerability.gif" width="800">
  
  
  
Exploit 2 - XSS Using Music Names
WP Version: 4.2
Similar to the above exploit, an admin, hacked admin, or insider could add javascript into the title of a piece of music in a playlist.
  Step 1: Admin adds music to their media library
  Step 2: Admin adds javascript in the name of the music
  Step 3: Admin creates a new post with a music playlist in it
  Step 4: Admin adds music with javascript in the name


  <img src="https://github.com/jesse-ables/Codepath-Week-7/blob/master/musicvulnerability.gif" width="800">
