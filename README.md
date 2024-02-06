
<html lang="en">
<head>
    
    <title>for my baby only</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .container {
            margin-top: 50px;
        }
        .btn {
            margin: 10px;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Valentine's Day!</h1>
        <h3> Can i take you on a date?</h3>
        <button class="btn" onclick="inviteDate('yes')">Yes</button>
        <button class="btn" onclick="inviteDate('no')">No</button>
        <div id="message"></div>
    </div>

    <script>
        function inviteDate(response) {
            var name = (" are u sure darling? (yes only)");
            if (response === 'yes') {
                document.getElementById("message").innerHTML = `thank you baby, iloveyousomuchh
                sorry kung busy ako that time pero babawi ako, d ako makakapunta sa feb 14
                pede po bang sa ibang araw nalang po pero i promise na pupunta ako`;
            } else {
                alert(`why naman no po:<`);
                
            }
        }
    </script>
</body>
</html>
