# Codepath-Week-7
Write up of vulnerabilities found in WordPress

Exploit 1 - XSS Using Posts and Comments
An admin or user can input a <script> tag into a post or comment for a post.
  
  https://imgur.com/a/bwt9j0E
  <img src="https://imgur.com/a/bwt9j0E" width="800">
  
  <blockquote class="imgur-embed-pub" lang="en" data-id="a/bwt9j0E"><a href="//imgur.com/bwt9j0E"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
