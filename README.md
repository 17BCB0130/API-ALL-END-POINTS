# API-ALL-END-POINTS


# GET #

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DELETE METHOD</title>
    <style>
        .align{
            text-align:center;
        }
    </style>
</head>
<body>
    <h1 class="align">JavaScript’s Fetch API</h1>
    <h2 class="align">DELETE method</h2>
    <script>
        fetch('https://jsonplaceholder.typicode.com/todos/1',{
            method:"DELETE"
        })
        .then(response => response.json())
        .then(data => console.log(data))

    </script>
</body>
</html>

