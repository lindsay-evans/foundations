# foundations
Styling a WebPage on my own.

This is a project from TOP on styling a webpage minus the training wheels. I've been working a lot on flexbox, which is (so far) the hardest part of CSS I've encountered yet. Hopefully I've got it down.

Image Credits:
Photo by Bich Tran: https://www.pexels.com/photo/black-laptop-beside-black-computer-mouse-inside-room-669996/

Photo by Magova: https://www.pexels.com/photo/shallow-focus-photo-of-red-and-brown-leaves-772520/

Photo by Ana M.: https://www.pexels.com/photo/white-mug-3152022/

Photo by Anna Tukhfatullina Food Photographer/Stylist: https://www.pexels.com/photo/white-and-orange-pumpkins-on-table-3094074/

Photo by Pixabay: https://www.pexels.com/photo/red-and-brown-plant-leaf-in-closeup-photo-235732/

Photo by Designecologist: https://www.pexels.com/photo/leaves-hang-on-rope-1389460/





<div class="heroimage">
                <img src="laptop.jpg" alt="laptop">
            </div>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foundations | The Odin Project</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header>
        <div class="header">
            <div class="logo">Header Logo</div>
                <div class="navbar">
                    <ul>
                        <li><a href="google.com">header link one</a></li>
                        <li><a href="google.com">header link two</a></li>
                        <li><a href="google.com">header link three</a></li>
                    </ul>
                </div>
            </div>
            <div class="herotext">
                <h1>This website is awesome</h1>
                <p class="subtext">This website has some subtext that goes here under the main title. It's a smaller font and the color is lower contrast.</p>
                <button>Sign up</button>
            </div>
            
        </div>
    </header>

    <main>
        <div class="random">
            <h2 class="information"><strong>Some random information.</strong></h2>
            <div class="container">
                <img scr="">
                <p>this is some subtext under an illustration or image</p>
            </div>
            <div class="container">
                <img src="">
                <p>this is some subtext under an illustration or image</p>
            </div>
            <div class="container">
                <img src="">
                <p>this is some subtext under an illustration or image</p>
            </div>
            <div class="container">
                <img src="">
                <p>this is some subtext under an illustration or image</p>
            </div>
        </div>
        <div class="testimonial">
            <blockquote><em>This is an inspiring quote, or a testimonial from a customer. Maybe it's just filling up space, or maybe people will actually read it. Who knows? All I know is that it looks nice.</em><br>
            <p>-Thor, God of Thunder</p></blockquote>
        </div>
        <div class="actioncontainer">
            <div class="action">
                <h3>Call to action! It's time!</h3><br>
                <p>Sign up for our product by clicking that button right over there!</p>
                <button class="action">Sign up</button>
            </div>
        </div>
    </main>
    <footer><div class="footer">Copyright &copy; The Odin Project 2021</div></footer>
</body>

* {
  font-family: roboto, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}

.header, .footer {
    background-color: #1F2937;
}

.header {
    display:flex;
    flex-direction:row;
    justify-content:space-around;
    align-items: center;
    background-color: #1F2937
}

.logo {
    font-size: 24px;
    color: #F9FAF8;
    font-weight: bold;
}

a {
    font-size: 18px;
    color: #E5E7EB;
    text-decoration: none;
    list-style-type: none;
    display:flex;
    flex-direction:row;
    justify-content:space-around;
    align-self:center;
}

.herotext {
    font-size: 18px;
    background-color:#1F2937;
    color: #E5E7EB;
    text-decoration: none;
    list-style-type: none;
    display:flex;
    flex-direction:row;
    justify-content:space-evenly;
    align-self:center;
}

h1 {
    align-self:flex-start;
}

p.subtext {
    align-self:flex-end;
}


img.heroimage {
    height:300px;
    width:300px;
    display:flex;
    flex-direction:row;
}

div.random {
    background-color: white;
    color: #1F2937;
}

h2.information {
    font-size: 36px;
    font-weight: bolder;
}

.container {
    display:flex;
    flex-direction:row;
    align-self:center;
}

div.testimonial {
    background-color: #E5E7EB;
}

blockquote {
    color: #1F2937;
    font-size: 36px;
    font-weight: lighter;
}

.actioncontainer {
    background-color: white;
}

div.action {
    background-color: #3882F6;
    color: #E5E7EB;
    margin-top: 50px;
    margin-bottom: 50px;
    margin-left: 75px;
    margin-right: 75px;
    display:flex;
    flex-direction:row;
    justify-content:space-around;
    align-items: center;
}

button.action {
    background-color: #3882F6;
    color: white;
    border-color: white;
    border-style: solid;
    border-radius: 10%;
    padding-left:15px;
    padding-right:15px;
    padding-top:5px;
    padding-bottom:5px;
    margin-left:10px;
    margin-right:10px;
}

.footer {
    color:#E5E7EB;
    text-align: center;
    font-size: x-small;
    padding:20px
}
</html>