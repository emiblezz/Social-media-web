
<html lang="en">
    <head>
        <style>
            body,html{
    width:100%;
    height:100%;
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}

/* Whole page */



/* navbar */
menu {
    height:100vh;
    width:100%;
    padding: 30px;
}

nav{
    display: flex;
    justify-content: space-between;
    padding-right:10px;
    padding-left:10px;
    padding-top:40px;
    align-text:center;
    flex-diction: row;
    background:gray;
    border-radius: 15px;
}
h1 {
    color: red;
    font-size:32px;
    display:flex;
    flex-direction:row;
}

nav ul li{
    list-style-type:none;
    display:inline-block;
    padding: 20px 10px;
}
nav ul li a{
    font-weight: bold;
    color: red;
    text-decoration: none;
}
nav ul li a:hover{
    color: blue;
    transition: 0.3s;
}
/* a tags */
a{
    text-decoration: none;
    color: palevioletred;
    font-size:28px;
}
/* form */
.form-box{
    width:380px;
    height:90vh;
    position:relative;
    margin:2% auto;
    background: gray;
    padding: 10px;
    overflow: hidden;
    border-radius:25px;
}

.button-box{
    width:220px;
    margin: 35px auto;
    position: relative;
    box-shadow: 0 0 20px 9px rgb(6, 175, 226);
    border-radius: 30px;
    display: flex;
}

.toggle-btn{
    padding: 10px 30px;
    cursor: pointer;
    background:transparent;
    border: 0;
    outline: none;
    position:relative;
    color: white;
}

#register .input-field{
    padding: 10px 0 0 0;
}

#btn{
    top: 0;
    left: 0;
    position: absolute;
    width: 110px;
    height: 100%;
    background: rgb(241, 20, 20);
    border-radius: 30px;
    transition:.5s;
}

.input-group-login{
    top: 150px;
    position: absolute;
    width:280px;
    transition:.5s;
}

.input-group-register{
    top: 120px;
    position: absolute;
    width:280px;
    transition:.5s;
}

.input-field{
    width:100%;
    padding: 10px 0;
    margin:5px 0;
    border-left: 0;
    border-top: 0;
    border-right:0;
    border-bottom: 1px solid rgb(158, 157, 157);
    outline: none;
    background: transparent;
}

.submit-btn{
    width: 85%;
    padding: 10px 30px;
    cursor: pointer;
    display: block;
    margin: auto;
    background:  rgb(241, 20, 20);
    border: 0;
    border-radius: 30px;
    color: white;
}

.check-box{
    margin: 30px 10px 34px 0px;
}

span{
    color:white;
    font-size:12px;
    bottom: 68px;
    position:absolute;
    margin: 0px;

}
::placeholder{
    color: silver;
}

#login{
    left: 50px;
}

#login input{
    color: white;
    font-size:15;
}

#register{
    left:450px;
    height:100vh;
}
#register input{
    color: white;
    font-size: 15;
}

#title1{
    margin: 0 auto;
    box-shadow: 0 0 10px 9px rgb(6, 175, 226);
    border-radius: 30px;
    background-color: red;
}
#txt-area{
    padding: 0;
    
}
.container {
    width:100%;
    height:100vh;
    over-flow: hidden;
    background-image:url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRQy5uH55VHWbW4mUGu3md6u9JlM-hIkxBbKg&usqp=CAU);
    background-size:cover;
    background-repeat: no-repeat;
    animation:change 30s infinite ease-in-out;
    justify-content: center;
    text-align: center;
    position:relative;
    background-position:center;
}
.content{
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%,-50%);
}
.content{
    font-size: 20px;
    letter-spacing:15px;
    color:white;
}
.content a{
    background:#85c1ee;
    color: white;
    border-radius:20px;
    font-size: 20px;
    padding: 10px 20px;
}
.content a:hover{
    background:purple;
}
@keyframes change{
    0%
    {
        background-image:url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQmhugjL9GU2Lt2cjVoTFeL3MzytdfmidRi2A&usqp=CAU);
    }
    20%
    {
        background-image:url(https://cdn1.vectorstock.com/i/1000x1000/18/40/social-network-background-with-media-icons-vector-1291840.jpg);
    }
    40%
    {
        background-image:url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSU-Po6MQOdRUrN8SsdM7nf5vlGjE8XW4A1oQ&usqp=CAU);
    }
    60%
    {
        background-image:url(https://media.istockphoto.com/vectors/social-network-vector-id486401982?k=20&m=486401982&s=612x612&w=0&h=IvF6B7ivk-nIh_wmg4ybm7QXb2bcnaULDnAx5iEZghI=);
    }
    80%
    {
        background-image:url(https://media.istockphoto.com/photos/digitizing-robot-hand-trying-to-catch-globe-picture-id1383940434?k=20&m=1383940434&s=612x612&w=0&h=O-mdi0ZjJQDZ8f_0Yrrk0QFsqUNwdyJ94H3bHmZ4Mn0=);
    }
    100%
    {
        background-image:url(https://media.istockphoto.com/photos/digitizing-robot-hand-trying-to-catch-globe-picture-id1383940434?k=20&m=1383940434&s=612x612&w=0&h=O-mdi0ZjJQDZ8f_0Yrrk0QFsqUNwdyJ94H3bHmZ4Mn0=);
    }

}
        </style>
        <meta charset="utf-8">
        <title>BroLite Login</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
    <div class="menu">
        <nav>
            <h1 class="logo">BRO LITE</h1>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">AboutUs</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact Us</a></li>
                <li><lable><button>Search</button><input type="search" value="search" placeholder="search here"></lable></li>
            </ul>
        </nav>
    </div>

    <div class="container">
        <div class="content">

            <div id="login-form" class="login-page">
                <div class="form-box">
                    <div class="button-box">
                        <div id="btn"></div>
                        <button type="button" onclick="loginBtn()" class="toggle-btn"> Log In</button>
                        <button type="button" onclick="registerBtn()" class="toggle-btn">Register</button>
                    </div>
                    <!--Login form. -->
                    <form id="login" class="input-group-login" onsubmit="login()" method="get" name="loginForm">
                        <input type="text" id="Login-UserName" class="input-field" placeholder="User Name" required name="username">
                        <input type="password" class="input-field" placeholder="Password" required name="password">
                        <input type="checkbox" class="check-box"><span>Remember Password</span>
                        <button type="submit" class="submit-btn">Log In</button>
                    </form>
                    <!--Registration form-->
                    <form id="register" class="input-group-register" method="get" onsubmit="signUp()" name="signupForm">
                        <input type="text" id="fName" class="input-field" placeholder="Full Name" required name="fname">
                        <input type="text" id="lName" class="input-field" placeholder="Email" required name="email">
                        <input type="text" id="uName" class="input-field" placeholder="User Name" required name="username">
                        <input type="password" id="Password" class="input-field" placeholder="Enter Password" required name="password">
                        <input type="password" id="cPassword" class="input-field" placeholder="Confirm Password" required name="cpassword">
                        <label for="pp" style="color: white; font-size: 14px; margin: 10px 0;">Profile picture</label>
                        <input type="file" name="pp" src="" alt="" name="pp">
                        

                        <input type="checkbox"  class="check-box" name="tc"><span>Terms & conditions</span>
                        <button type="submit" id="submit" class="submit-btn">Continue</button>
                    </form>

                </div>
            </div>
        </div>
    </div>
        <script>
            var x= document.getElementById("login");
            var y= document.getElementById("register");
            var z= document.getElementById("btn");

            function registerBtn(){
                x.style.left='-400px';
                y.style.left='50px'; 
                z.style.left='110px';
            }

            function loginBtn(){
                x.style.left='50px';
                y.style.left='450px';
                z.style.left='0px';
            }
        </script>
        <script src="https://github.com/emiblezz/Social-media-web/blob/main/JS%20WEB%20assignment/JS%20WEB%20assignment/auth.js"></script>
    </body>
    </html>
