 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ijara Bursary Application Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 50%;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h2 {
            text-align: center;
            color: #2C3E50;
        }
        label {
            font-weight: bold;
            color: #2C3E50;
        }
        input[type="text"], input[type="email"], input[type="number"], textarea {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group input[type="submit"] {
            background-color: #3498db;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }
        .form-group input[type="submit"]:hover {
            background-color: #2980b9;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>Ijara Bursary Application Form</h2>
    <form action="#" method="POST">
        <!-- Personal Details Section -->
        <div class="form-group">
            <label for="fullName">Full Name:</label>
            <input type="text" id="fullName" name="fullName" required placeholder="Enter your full name">
        </div>

        <div class="form-group">
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
        </div>

        <div class="form-group">
            <label for="email">Email Address:</label>
            <input type="email" id="email" name="email" required placeholder="Enter your email address">
        </div>

        <div class="form-group">
            <label for="contact">Contact Number:</label>
            <input type="text" id="contact" name="contact" required placeholder="Enter your contact number">
        </div>

        <!-- Educational Background Section -->
        <div class="form-group">
            <label for="schoolName">School/University Name:</label>
            <input type="text" id="schoolName" name="schoolName" required placeholder="Enter your school or university name">
        </div>

        <div class="form-group">
            <label for="program">Program of Study:</label>
            <input type="text" id="program" name="program" required placeholder="Enter the program you're enrolled in">
        </div>

        <div class="form-group">
            <label for="year">Year of Study:</label>
            <input type="number" id="year" name="year" required placeholder="Enter your current year of study" min="1" max="5">
        </div>

        <!-- Financial Information Section -->
        <div class="form-group">
            <label for="monthlyIncome">Monthly Family Income:</label>
            <input type="number" id="monthlyIncome" name="monthlyIncome" required placeholder="Enter your family monthly income" min="0">
        </div>

        <div class="form-group">
            <label for="tuitionFee">Tuition Fee (Per Year):</label>
            <input type="number" id="tuitionFee" name="tuitionFee" required placeholder="Enter your annual tuition fee" min="0">
        </div>

        <div class="form-group">
            <label for="otherFinancialAssistance">Other Financial Assistance (if any):</label>
            <textarea id="otherFinancialAssistance" name="otherFinancialAssistance" rows="4" placeholder="Enter any other financial assistance you're receiving"></textarea>
        </div>

        <!-- Declaration Section -->
        <div class="form-group">
            <label for="declaration">
                <input type="checkbox" id="declaration" name="declaration" required>
                I hereby declare that all information provided is true and correct to the best of my knowledge.
            </label>
        </div>

        <div class="form-group">
            <input type="submit" value="Submit Application">
        </div>
    </form>
</div>

</body>
</html>




        <label for="fileUpload">Choose the file you want to post (Image or other file):</label>
        <input type="file" id="fileUpload" name="fileUpload" accept="image/*, application/pdf"><br><br>

        <label for="fileDescription">What does the file contain:</label><br>
        <textarea id="fileDescription" name="fileDescription" rows="4" cols="50" required></textarea><br><br>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
