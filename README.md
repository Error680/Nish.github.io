<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ki Re Vera Kmn Achis</title>
</head>
<body>
    <h1>Welcome to Ki Re Vera Kmn Achis</h1>
    <p>Choose an option:</p>
    <button onclick="showGood()">Good</button>
    <button onclick="showBad()">Bad</button>

    <div id="result"></div>

    <script>
        function showGood() {
            document.getElementById('result').innerHTML = '<img src="rose.png"><p>Wahh</p>';
        }

        function showBad() {
            document.getElementById('result').innerHTML = '<p>Oh no, Bad option selected!</p>';
        }
    </script>
</body>
</html>
# Nish.github.io
