# newproject
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>signup</title>
</head>
<body>
    <h1>SIGN UP</h1>
    <form method="POST">
        {% csrf_token %}
        {{form.as_p}}
        <input type="submit" value="submit">
    </form>
</body>
</html>
