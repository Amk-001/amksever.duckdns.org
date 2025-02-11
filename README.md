<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Template</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #3b5998;
            color: white;
            padding: 10px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: calc(100vh - 120px);
        }
        iframe {
            width: 50%;
            height: 300px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: white;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <!-- Navigation Menu -->
    <nav>
        <a href="home.html" target="content-frame">Home</a>
        <a href="mypage.html" target="content-frame">My Page</a>
        <a href="public.html" target="content-frame">Public Page</a>
        <a href="about.html" target="content-frame">About</a>
    </nav>

    <!-- Center Content -->
    <div class="container">
        <!-- Dialog Box Frame -->
        <iframe src="login.html" name="content-frame"></iframe>
    </div>

</body>
</html>
