# CSS-Grid-random-images
CSS Grid with random images from Unspalsh
force refresh every few seconds
//unsplash.it/500/500



<html>
<head>
    <meta http-equiv="refresh" content="5">
    <link rel="stylesheet" href="style.css">
</head>
<body>
<div class="wrapper">
    <div class="card c1"><img src="//unsplash.it/300/300"></div>
    <div class="card c2"><img src="//unsplash.it/301/300"></div>
    <div class="card c3"><img src="//unsplash.it/300/301"></div>
    <div class="card c5"><img src="//unsplash.it/300/299"></div>
    <div class="card c4"><img src="//unsplash.it/299/650"></div>
    <div class="card c6"><img src="//unsplash.it/301/299"></div>
    <div class="card c7"><img src="//unsplash.it/299/301"></div>
    <div class="card c8"><img src="//unsplash.it/300/650"></div>
    <div class="card c9"><img src="//unsplash.it/301/301"></div>
    <div class="card c10"><img src="//unsplash.it/298/298"></div>
    <div class="card c11"><img src="//unsplash.it/298/299"></div>
    <div class="card c12"><img src="//unsplash.it/298/300"></div>
    <div class="card c13"><img src="//unsplash.it/298/301"></div>
    <div class="card c14"><img src="//unsplash.it/299/298"></div>
    <div class="card c15"><img src="//unsplash.it/300/298"></div>
    <div class="card c16"><img src="//unsplash.it/301/298"></div>
    <div class="card c17"><img src="//unsplash.it/299/299"></div>
    <div class="card c18"><img src="//unsplash.it/299/300"></div>
</div>
</body>
</html>




*{
    padding:0;
    margin:0;
}
.card{
    background: #ffffff00;
    
}
img{
    border-radius: 15px;;
}
.wrapper{
    padding-top:50px;
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    grid-gap:50px;
    text-align: center;
    background: center no-repeat url(cool-background.png);
    background-size: cover;
    background-attachment: fixed;
}
.c8{
    grid-row:span 2;
}
.c4{
    grid-row:span 2;
}