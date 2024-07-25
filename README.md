<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>File Post Form</title>
</head>
<body>
  <form action="#" method="POST" enctype="multipart/form-data">
    <label for="friendName">Enter name of your friend</label><br>
    <input type="text" id="friendName" name="friendName"><br><br>

    <label for="fileUpload">Choose the file you want to post to your friend</label><br>
    <input type="file" id="fileUpload" name="fileUpload"><br><br>
    
    <label>What does the file contain</label><br>
    <input type="radio" id="fileTypeImage" name="fileType" value="image">
    <label for="fileTypeImage">Image</label><br>

    <input type="radio" id="fileTypeSourceCode" name="fileType" value="sourcecode">
    <label for="fileTypeSourceCode">Source code</label><br>

    <input type="radio" id="fileTypeBinaryCode" name="fileType" value="binarycode">
    <label for="fileTypeBinaryCode">Binary code</label><br><br>

    <input type="submit" value="Submit query">
  </form>
</body>
</html>
