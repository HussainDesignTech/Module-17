# Module-17
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial">
    <title> Hussain Portfolio </title>
    <link rel="stylesheet" href="style.CSS">
</head>
<body>
    <nav>
        <label class="logo">Hussain Alyousif</label>
        <ul>
            <li><a href="#" class="active">Home</a></li>
            <li><a href="#">Home</a></li>
            <li><a href="#">Portfolio</a></li>
            <li><a href="#">Resume</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">About</a></li>
        </ul>
    </nav>
    <footer>
        <div class="footer">
            <a href="#" class="in">LinkedIn</a>
        </div>
    </footer>
</body>
</htm1>
-------------------------
CSS
*{
    margin: 0;
    padding: 0;
    text-decoration: none;
    list-style: none;
    box-sizing: border-box;
}
body{
    font-family: 'Times New Roman', Times, serif;
}
nav{
    background-color: #4682b4;
    height: 80px;
    width: 100%;
}
label.logo{
    color: white;
    font-size: 36px;
    line-height: 80px;
    padding: 0 100px;
    font-weight: bold;
}
nav ul {
    float: right;
    margin-right: 50px;
}
nav ul li{
    display: inline-block;
    line-height: 80px;
    margin: 0;
}
nav ul li a{
    color: white;
    font-size: 1rem;
    border-radius: 3px;
}
a.active,a:hover{
    color: rgb(7, 23, 95);
    transition: 0.5s;
}
.footer{
    background-color: #4682b4;
    height: 150px;
    width: 100%;
    bottom: 0px;
}
.checkbtn{
    font-size: 31px;
    color: white;
    float: right;
    line-height: 80px;
    margin-right: 40px;
    cursor: pointer;
    display: none;
}
#check{
display: none;
}
