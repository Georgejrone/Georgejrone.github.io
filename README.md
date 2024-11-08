<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Start Page</title>
    <style>
        /* Basic styling for the body */
        body {
            display: flex; /* Use Flexbox for centering */
            justify-content: center; /* Center horizontally */
            align-items: center; /* Center vertically */
            height: 100vh; /* Full height of the viewport */
            margin: 0; /* Remove default margin */
            background-color: #f0f0f0; /* Light gray background */
        }

        /* Styling for the button */
        .start-button {
            padding: 15px 30px; /* Padding around the button */
            font-size: 20px; /* Larger font size */
            color: white; /* White text color */
            background-color: #007bff; /* Bootstrap primary color */
            border: none; /* No border */
            border-radius: 5px; /* Rounded corners */
            cursor: pointer; /* Change cursor to pointer on hover */
            transition: background-color 0.3s; /* Smooth transition for background color */
        }

        /* Button hover effect */
        .start-button:hover {
            background-color: #0056b3; /* Darker shade on hover */
        }
    </style>
</head>
<body>

    <!-- Button that links to Start.html -->
    <a href="Start.html">
        <button class="start-button">Start</button>
    </a>

</body>
</html>
