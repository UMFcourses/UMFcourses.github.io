---
permalink: courses/course1/candidate/
layout: splash
---
<html>
<head>
    <title>Contact</title>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/water.css@2/out/water.css">
</head>

<body>
<h1>Contact</h1>
    
<form method="post" action="send-email.php">
    Name:<br>
    <input type="text" name="name"><br>
    E-mail:<br>
    <input type="text" name="mail"><br>
    Comment:<br>
    <input type="text" name="comment" size="50"><br><br>
    <label for="myfile">Provide a Cv:</label>
    <input type="file" id="myfile" name="CV"><br>
    <label for="myfile">Provide a Cover letter:</label>
    <input type="file" id="myfile" name="Cover Letter"><br>
    <input type="submit" value="Send">
    <input type="reset" value="Reset">
</form>

</body>
</html>
