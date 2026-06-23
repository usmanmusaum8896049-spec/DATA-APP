<!DOCTYPE html>
<html>
<head>
    <title>Login App</title>
</head>
<body>
    <h2>Login</h2>

    <input type="email" id="email" placeholder="Email"><br><br>
    <input type="password" id="password" placeholder="Password"><br><br>

    <button onclick="login()">Login</button>

    <script>
        function login() {
            let email = document.getElementById("email").value;
            alert("Welcome " + email);
        }
    </script>
</body>
</html>