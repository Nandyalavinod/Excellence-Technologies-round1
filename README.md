<!DOCTYPE html>
<html>
<head>
    <title>Find Even numbers in Array using JavaScript</title>
</head>
<body>
    <p>
        Using for loop to get even numbers in an Array.
    </p>
</body> 
<script>
    function getEvenNumbers() {
        var arr = [1, 2, 3, 4, 5, 6];

        for (var i = 0; i < arr.length; i++) {
            if (arr[i] % 2 === 0) {
                document.writeln(arr[i] + "<br />");
            }
        }
    }
    </script>
    </html
