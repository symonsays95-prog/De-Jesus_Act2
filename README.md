<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TSA3</title>
    <link rel="stylesheet" href="grid.css">
    <Link rel="stylesheet" href="style2.css">
</head>
<body>

    <main>
        <header class="title">
            <h1>SININGCHIVE'S PROJECTS</h1>
        </header>

    <section id="main">
        <h2>ARTWORKS</h2>
            <ul>
            <li>
                <p>About You by The 1975</p>
                <img src="c:\Users\Symon\Downloads\about you.jpg" width="300"/>
            </li>
            <li>
                <p>FML by SEVENTEEN</p>
                <img src="c:\Users\Symon\Downloads\fml black.jpg" width="300"/>
            </li>
            <li>
                <p>Multo by Cup Of Joe</p>
                <img src="c:\Users\Symon\Downloads\multo 2.jpg" width="300"/>
            </li>
            <li>
                <p>Come Inside Of My Heart by IV Of Spades</p>
                <img src="c:\Users\Symon\Downloads\come inside of my heart.jpg" width="300"/>
            </li>
            <li>
                <p>Endgame by Taylor Swift (feat. Ed Sheeran & Future)</p>
                <img src="c:\Users\Symon\Downloads\endgame 1.jpg" width="300"/>
            </li>
            <li>
                <p>Dilaw by Maki</p>
                <img src="c:\Users\Symon\Downloads\dilaw.jpg" width="300"/>
            </li>
            </ul>
</section>
    </main>

    <nav class="navbar">
        <ul>
            <li><a href="#intro">About Me</a></li>
            <li><a href="#main">Projects</a></li>
            <li><a href="https://www.instagram.com/">Instagram</a></li>
        </ul>
    </nav>

    <aside>
        <header>
            <h2>ABOUT ME</h2>
        </header>
        <div>
            <img src="c:\Users\Symon\OneDrive\Pictures\Screenshots\Screenshot 2025-10-12 145112.png" width="200"/>
                <p>Hello! I am <em>SININGCHIVE</em>, this is my archives of my artworks and projects. I aspire to be a graphic designer and in this portfolio, I will be showcasing how far my skills have gone in graphic designing.</p>
        </div>
        <div>
            <h2>WHO IS SININGCHIVE?</h2>
                <p>My name is Symon R. De Jesus. I am study MMA (Multimedia Arts) in FEU Tech. 1 year ago, I started to practice graphic designing. It was solely for acedemic purposes, but I wanted to do more outside of a school project.
            Hence, the creation of <em>SININGCHIVE.</em> My name is derived from two words: SINING + CHIVE. My initial name is supposed to be ARTCHIVES, but it was too common. So, I translated ART into tagalog which is SINING and combined it with the second syllable of the word archive "CHIVE".
            I make posters with a theme. Most of the time, my posters are linked with the topic of a specific song. I used to create in Canva. But, now I primarily use Adobe Photoshop. I also use Pinterest to get ideas and inspiriation. My projects doesn't stick with one type of media.
            Some are motion picutes and some are static posters. And the style I use in my posters are diverse.</p>
        </div>
        <div>  
            <h2>INSTAGRAM</h2>
                <p>If you want to see more of my artworks, you can check out my Instragram!</p>
                    <a href="https://www.instagram.com/siningchive/">
                        <button style="font-size: 15px; background-color: burlywood; color: black; border-radius: 5px;">CLICK HERE!</button></a>
        </div>
    </aside>

    <footer>
        <h4>Contacts</h4>
            <p>Facebook: Symon De Jesus</p>
            <p>Instagram: @symonrdj</p>
            <p>Personal Email: symonsays95@gmail.com</p>
            <p>School Email: srdejesus@fit.edu.ph</p>
    </footer>
</body>
</html>



nav{
    background-color: rgb(61, 80, 116);
    padding: 20px;
    margin-bottom: 10px;
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
    text-transform: uppercase;
    font-weight: bold;
}
.navbar ul{
    list-style: none;
    padding: 0px;
    margin: 0px;
    overflow: hidden;
    text-align: center;
}
.navbar a{
    color: white;
    text-decoration: none;
    padding: 5px;
    display: block;
    text-align: center;
}
.navbar a:hover{
    background-color: blanchedalmond;
}
.navbar ul li{
    display: inline-block;
}
aside {
    background-color: lightskyblue;
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
    margin-right: 20px;
}
header {
    text-align: center;
    font-size: larger;
}
footer {
    background-color: navy;
    grid-area: footer;
    color: azure;
    padding: 0px;
    margin-left: 5px;
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
}
header {
    font-family: Arial, Helvetica, sans-serif;
}
p {
    text-align: justify;
    margin: 10px;
}
main {
    background-color: beige;
    margin-bottom: 10px;
}
.title {
    background-color: cornflowerblue;
}
#main {
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
}



body {
    min-height: 100vh;
    display: grid;
    grid-template-columns: 300px 1fr;
    grid-template-rows: auto 1fr auto;
    grid-template-areas:
    "navbar navbar"
    "sidebar main"
    "sidebar footer";
}
nav {
    grid-area: navbar;
}
aside {
    grid-area: sidebar;
}
main {
    grid-area: main;
}
footer {
    grid-area: footer;
}
