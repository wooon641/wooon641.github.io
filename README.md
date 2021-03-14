# kokoa_first-clone
First-clone_Kokoa
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="css/styles.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Kokoa Talk</title>
</head>
<body>
    <div class="status-bar">
        <div class="status-bar__column">
            <span>No Service</span>
            <i class="fas fa-wifi"></i>
        </div>
        <div class="status-bar__column">
            <span>08:24</span>
        </div>
        <div class="status-bar__column">
            <span>80%</span>
            <i class="fas fa-battery-three-quarters fa-lg"></i>
            <i class="fas fa-bolt"></i>
        </div>
    </div>

    <header class="welcome-header"> 
        <h1 class="welcome-header__title">Welcome to KokoaTalk</h1>
        <p class="welcome-header__text">
            If you have a Kokoa Account, log in with your email or phone number.
        </p>
    </header>

    <form action="friends.html" method="get" id="login-form">
        <input name="username" type="text" placeholder="Email or phone number" />
        <input name="password" type="password" placeholder="Password" />
        <input type="submit" value="Log In" />
        <input type="submit" value="Sign Up" />
        <a href="#">Find Kokoa Account or Password</a>
    </form>

    <div id="no-mobile">
        <span>Your screen is too big</span>
    </div>

    <script
      src="https://kit.fontawesome.com/6478f529f2.js"
      crossorigin="anonymous"
    ></script>
</body>
</html>
