<!DOCTYPE html>
<head>
<title>Piscines</title>
<script src="/assets/jquery.js"></script>
<link href='https://fonts.googleapis.com/css?family=Londrina+Shadow' rel='stylesheet' type='text/css'>
<style>
body {
  font-family: Helvetica;
  margin: 0 auto;
  max-width: 600px;
  background:url("http://www.lenfantdeau.be/wp-content/uploads/2014/03/fond-piscine1.jpg");
  
}
div {
  height: 280px;
  background-size: cover;
  position: relative;
  margin: 10px 0 0 0;

}
h1 {
  font-family: 'Rancho'; 
  text-align: center;
  font-size: 75px;
  color:#1C2423;
  margin: 40px 0 0 0;
}
h2 {
  text-align: center;
  font-family:'dancing script';
  font-size:30px;
  color: #1C2423;
  margin: 0px 0 0px 0;
}
h4  {
  text-align:center;
}
p {
  color: rgba(255,255,255,1);
  background: black;
  background: linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  background: -webkit-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  background: -moz-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  padding: 2px;
  line-height: 50px;
  text-align: justify;
  bottom: 0;
  margin: 0;
  height: 50px;
  transition: height .5s;
  -webkit-transition: height .5s;
  -moz-transition: height .5s;
}

small {
  opacity: 0;
}

.show-description p {
  height: 150px;
}

.show-description small {
  opacity: 1;
}

.ovales{
  background-image: url("http://www.guide-piscine.fr/medias/image/la-piscine-ovale-9538-468-0.jpg");
}
.rectangulaires{
  background-image: url("http://www.piscinespa.com/site/userfiles/images/actualites/Piveteaubois_rect.jpg");
}
.carrees{
  background-image: url("http://www.photopiscine.net/wp-content/uploads/2014/02/petite-piscine-carre-300x210.jpg");
}
.rondes{
  background-image:url("http://img.1.im6.fr/04305944-photo-piscine-ronde-waterair.jpg");
}
.price {
  float: right;
}

input {
      text-align:center;
      border: 0;
      padding: 10px;
      font-size: 15px;
      
    }
@media (max-width: 500px) {
  h1 {
    font-size: 50px;
    margin-top: 20px;
    line-height: 40px;
  }
  h2 {
    font-size: 20px;
    margin: 20px 0 30px 0;
  }
  div {
    margin: 20px 12px 0 12px;
  }
  p {
    font-size: 20px;
    line-height: 24px;
  }
  small {
    font-size: 16px;
  }
  
}

</style>

</head>

<body>
<h1><strong><u>Aux mille flots bleus</u></strong></h1>
<h2><em>Fabricant de piscines enterrees depuis 1977<em></h2>
<h4>(livraison dans toute la France)</h4>
<center><input type="email" placeholder="Demander un devis gratuit">
  <input type="submit"></center>


<div class="ovales">
  <p>Les "ovales" <span class="price">A partir de 7 000 Euros</span>
  </p>
</div>

<div class="rectangulaires">
  <p>Les "Rectangulaires" <span class="price">A partir de 7 500 Euros</span>
  </p>
</div>
  
<div class="carrees">
  <p>Les "Carrees" <span class="price">A partir de 4 000 Euros</span>
  </p>
</div>

<div class="rondes">
  <p>Les "Rondes" <span class="price">A partir de 5 500 Euros</span><br />
</p>

</div>

</body>
