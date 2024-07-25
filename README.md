<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Friend Form</title>
</head>
<body>
    <h2>Enter name of your friend.</h2>
    <form action="#" method="post" enctype="multipart/form-data">
        <label for="friendName">Friend's Name:</label>
        <input type="text" id="friendName" name="friendName" required><br><br>

        <label for="fileUpload">Choose the file you want to post (Image or other file):</label>
        <input type="file" id="fileUpload" name="fileUpload" accept="image/*, application/pdf"><br><br>

        <label for="fileDescription">What does the file contain:</label><br>
        <textarea id="fileDescription" name="fileDescription" rows="4" cols="50" required></textarea><br><br>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
