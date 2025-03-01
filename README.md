#All India Schilarship
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>1st PUC Scholarship</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            background-color: #f4f4f4;
        }
        #main-content {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            margin: auto;
        }
        #hidden-message {
            display: none;
            font-size: 24px;
            font-weight: bold;
            color: red;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background: blue;
            color: white;
            border: none;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background: darkblue;
        }
    </style>
</head>
<body>

    <div id="main-content">
        <h1>1st PUC Scholarship</h1>
        <p>All India Free Scholarship Program</p>
        <p>Apply now for a chance to receive financial aid for your education.</p>
        <button onclick="revealPrank()">Apply Now</button>
        <p id="hidden-message">DRISH NA KAAR PATHLE</p>
    </div>

    <script>
        function revealPrank() {
            document.getElementById("hidden-message").style.display = "block";
        }
    </script>

</body>
</html>