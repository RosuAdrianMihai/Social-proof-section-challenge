# Social-proof-section-challenge

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Social proof section challenge hub</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=
Spartan:wght@400;500;700&display=swap" 
rel="stylesheet">
    <link rel="stylesheet" href="Pagina test.css">
</head>
<body>
    
<div class="container">

<div class="up-part">

<div class="main">

    <h2>10,000+ of our users love our products.</h2>
    <p>We only provide great products combined with 
        excellent customer service. See what our satisfied 
        customers are saying about our services.</p>

</div>

<div class="review">

<div class="stars" id="s1">
<div class="interior">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <p>Rated 5 Stars in Reviews</p>
</div>
</div>

<div class="stars" id="s2">
<div class="interior">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <p> Rated 5 Stars in Report Guru</p>
</div>
</div>

<div class="stars" id="s3">
<div class="interior">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <img src="icon-star.svg" alt="">
    <p>Rated 5 Stars in BestTech</p>
</div>
</div>

</div>


</div>

<div class="bottom-part">

<div class="card" id="c1">

    <div class="important">

    <img src="image-colton.jpg" alt="">

    <div class="ver">

    <div class="name"> 
        Colton Smith</div>

        <div class="buyer"> Verified Buyer </div>

        </div>

    </div>

    <p>"We needed the same printed design as the one we
         had ordered a week prior. Not only did they find 
         the original order, but we also received it in
          time. Excellent!"</p>

</div>

<div class="card" id="c2">

<div class="important">

    <img src="image-irene.jpg" alt="">
    <div class="ver">

    <div class="name"> Irene Roberts</div> 
    <div class="buyer"> Verified Buyer </div> 
</div>

</div>

    <p>"Customer service is always excellent and very
         quick turn around. Completely delighted with 
         the simplicity of the purchase and the speed 
         of delivery."</p>

</div>

<div class="card" id="c3">
<div class="important">
    <img src="image-anne.jpg" alt="">
<div class="ver">
    <div class="name"> Anne Wallace </div> 
    <div class="buyer"> Verified Buyer </div> 
</div>
</div>
    <p>"Put an order with this company and can only praise
         them for the very high standard. Will definitely use 
         them again and recommend them to everyone!"</p>

</div>

</div>

</div>

</body>
</html>


@media (min-width:376px)
{
    body{
        display:flex;
        align-content:center;
        justify-content: center;
}

.container{
    display:grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: auto;
    padding:3%;
    row-gap: 4%;
}

#c2{
    margin-top:25px;
}

#c3{
    margin-top:50px;
}

.card{
    border-radius:15px;
    padding:2%;
    height:200px;
}

#s2{
    margin-left:40px;
}

#s3{
    margin-left:80px;
}

.main{
    grid-column:1/2;
}

.review{
    margin-top:7%;
    grid-column:2/3;
    align-self: center;
    
}

.bottom-part{
    display:flex;
    grid-column: 1/4;
    grid-row: 2/3;
    column-gap:3%;
}

.up-part{
    display:grid;
   grid-template-columns: 1fr 1fr;
    grid-column: 1/4;
    column-gap:15%;
}

.interior{
    display:flex;
    margin-bottom:5%;
}
.stars{
    width:450px;
}

.interior img{
    align-self:center;
}

.interior p{
    padding-left:4%;
}

}

@media (max-width:375px)
{

}



body{
    font-size:15px;
    font-family: 'Spartan', sans-serif;
    margin:0px;
}

.interior{
    margin-left:30px;
}

.card{
    background:hsl(300, 43%, 22%);
    color:white;
    
}

.name{
    color:white;
}

.buyer{
    color: hsl(333, 80%, 67%);
}

.stars{
    background: hsl(300, 24%, 96%);
    color: hsl(300, 43%, 22%);
    border-radius: 10px;
}

h2{
    color:hsl(300, 43%, 22%);
    font-size:35px;
}

.main p{
    color:hsl(303, 10%, 53%);
    width:79%;
}

.card img{
    border-radius:50%;
}

.important{
    display:flex;
   align-content: center;
}

.ver{
    margin-left:20px;
    margin-top:20px;
}
