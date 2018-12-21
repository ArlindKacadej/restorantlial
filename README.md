# restorantlial
Lial Restaurant webpage
<html>
<head>
  <title>Food</title>
	<link href="bootstrap-4.1.3-dist/css/bootstrap-theme.min.css" rel="stylesheet">
	<link href="bootstrap-4.1.3-dist/css/bootstrap.min.css" rel="stylesheet">
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.6.3/css/all.css" integrity="sha384-UHRtZLI+pbxtHCWp1t77Bi1L4ZtiqrqD80Kn4Z8NTSRyMA2Fd33n5dQ8lWUE00s/" crossorigin="anonymous">
  <style>
  *
{
	margin:0;
	padding:0;
}
.row
{
	max-width:1140px;
	margin:0 auto;
}

body
{
	font-family:tahoma;
}
.hero
{
	position:absolute;
	width:1140px;
	top:50%;
	left:50%;
	transform:translate(-50%,-50%);
}
header
{
	background-image:url(https://www.wideopeneats.com/wp-content/uploads/2016/12/days-order-seafood-restaurant.png);
	height:100vh;
	background-position:center;
	background-size:cover; 
	background-attachment:fixed;
}
h1
{
    color:brown;
	font-weight:bold;
	text-align:center;
	font-family:"MV Boli";
	text-shadow: -2px 0 white, 0 2px white, 2px 0 white, 0 -2px white;
}


.main-nav
{
	list-style:none;
	float:right;
	margin-top:60px;
	background-color:brown;
	border-top: 2px solid #000;
	border-bottom:2px solid #000;
}


.main-nav li
{
	display:inline-block;
	margin-left:20px;
}

.main-nav li a
{
	color:white;
	text-decoration:none;
	font-size:150%;
	font-weight:bold;
}

.main-nav li a:hover
{
	color:#e67e22;
	border-bottom:2px solid #e67e22;
	transition:all 0.5s ease-in;
	padding:15px 0;
}
.logo img
{
	height:100px;
	float:left;
	margin-top:30px;
}


.btn
{
	
	border:1px solid #e67e22;
	padding:10px 30px;
	color:#e67e22;
	text-decoration:none;
	border-radius:12px;
	margin-right:15px;
}

.button-awesome
{
	margin-top:50px;
	text-align:center;
}

.btn-half
{
	background-color:#e67e22;
	color:white;
}

.btn-full:hover
{
	background-color:#e67e22;
	color:white;
	transition:all 0.5s ease-in;
}

.copy 
{
	width:70%;
	margin-left:15%;
	margn-bottom:20px;
}


.features h3
{
	margin-top:80px;
	margin-bottom:30px;
}

h3:after
{
	width:100px;
	height:2px;
	background-color:#e67e22;
	display:block;
	content: " ";
	margin:0 auto;
	margin-top:30px;
	
	
}


.arranging
{
	text-align:justify;
}


.features i
{
	font-size:40px;
	color:#e67e22;
	margin-left:40%;
}

.features h4
{
	margin-left:100px;
}

.meal-showcase
{
	list-style:none;
	width:100%;
	margin-left:;
}

.meal-showcase li
{
	display:block;
	width:25%;
	float:left;
}

.meal-photo
{
	width:100%;
	margin:0;
	overflow:hidden;
}

.meal-photo img
{
	width:100%;
	height:250px;
	transform:scale(1.15);
	transition:all 0.5s;
}

.meal-photo img:hover
{
	transform:scale(1.05);	
}

.meal
{
	margin-top:80px;
}

.pic img
{
	width: 40%;
	margin-left:50%;
	margin-top:50px;
}

.works-step
{
	margin-top:5px;
}

.works-step div
{
	border:1px solid #e67e22;
	display:inline-block;
	border-radius:50%;
	width:50px;
	height:50px;
	text-align:center;
	line-height:50px;
}

.works-step img
{
	width:130px;
	height:40px;
	margin-right:20px;
}

.clearfix
{
	zoom:1;
}

.clearfix:after
{
	visibility:hidden;
	content:".";
	height:0;
	display:block;
	clear:both;
}

.mobile
{
	margin-top:60px;
}

.cities
{
	margin-top:100px;
}

.cities img
{
	width:100%;
	margin-top:50px;
	height:170px;
}

.cities i
{
	color:#e67e22;
}

.testimonials
{
	margin-top:80px;
	background-image:linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)),url(https://t4.ftcdn.net/jpg/01/07/76/95/240_F_107769585_roi7NSdWxxaaeBx59tAuP43h15SJsY5Z.jpg);
	padding-top:80px;
	padding-bottom:60px;
	color:white;
	background-attachment:fixed;
}

.testimonials p
{
	color:white;
	line-height:25px;
	text-align:justify;
	margin-top:40px;
}
.testimonials cite img 
{
	width:50px;
	height:50px;
	border-radius:50%;
	margin-right:10px;
}

.btn-block
{
	background-color:#e67e22;
	color:white;
	border-radius:4px;
	margin-top:20px;
}

.gap
{
	margin-top:40px;
}

.form
{
	margin-top:40px;
}

.col-sm-3 {
  display: flex;
  width:60px;
  height:60px;
}

.ul {
  list-style: none;
  
}


  </style>
</head>
<body>
  <header>
  <div class="row">
	<div class="logo">
	<img src="data:image/jpeg;base64,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">
	</div>
  <ul class="main-nav">
		<li><a href="">MENU</a></li>
		<li><a href="">REZERVIME</a></li>
		<li><a href="">KONTAKTI</a></li>
		<li><a href="">RRETH NESH</a></li>
		
  </ul>
  <div class="hero">
    <h1>RESTORANT "LIAL"<br>AROME DETI!</h1>
	<div class="button-awesome">
	<a href="" class="btn btn-half">Me teper</a>
	<a href="" class="btn btn-full">Cfare ka per te ngrene?</a>
	</div>
  </div>
  </header>
  
  <section class="features">
  <h3 class="text-center">MIRESEVINI NE RESTORANT "LIAL"</h3>
  <p class="copy">
  I pozicionuar ne buze te detit, resturanti yne eshte vendi ideal nese deshironi te shijoni ne maksimum produktet e fresketa te detit.
  Te ne, cilesia e kuzhines mesdhetare bashkohet me ambjentet komforte dhe pamjen magjepsese te detit Adriatik.
  Mbi te gjitha, ne jemi ketu per te vazhduar traditen!
  </p>
  
  
  <div class="container">
	<div class="row">
	<div class="col-md-4">
		<i class="fa fa-map"></i>
		<h4>Vendndodhja</h4>
	<p class="arranging">
	Restorant Lial ndodhet ne Lagjen nr.1 ne Durres, ne zonen e plazhit Currila, buze detit, ne ambjentet e ndterteses se Hotel Ferrara.
	</p>
	</div>
	<div class="col-md-4">
		<i class="fa fa-camera"></i>
		<h4>Rreth nesh</h4>
	<p class="arranging">
	Restorant Lial u hap ne vitin 1995, ne rrugen e Currilave ne Durres.
	Eksperienca 23 vjecare na ka mesuar se cdo restorant i suksesshem ve ne rradhe te pare kerkesat e klientit.
	Prandaj, prioriteti yne eshte dhe do te jete kenaqesia e klientit nen cilesine e kuzhines sone. 
	</p>
	</div>
	<div class="col-md-4">
		<i class="fa fa-envelope"></i>
		<h4>Kontakti</h4>
	<p class="arranging">
	Email:arlind.kacadej@outlook.com<br>
	Numri i telefonit: 069 52 52 563<br>
	Facebook: RestorantLial<br>
	Instagram: restorantlial<br>
	<div class="row">
	<ul class="col-sm-4">
		<li class="col-sm-3">
			<img src="https://is3-ssl.mzstatic.com/image/thumb/Purple128/v4/f4/a2/c3/f4a2c31a-84da-6b6f-5def-fe6a4b515828/Prod-1x_U007emarketing-85-220-0-5.png/246x0w.jpg">
		</li>
		<li class="col-sm-3">
			<img src="https://www.facebook.com/images/fb_icon_325x325.png">
		</li>
	</ul>
	</div>
	</p>
	</div>
  </section>
  
  <section class="meal">
  <h2 class="text-center">Menu</h2>
  <ul class="meal-showcase clearfix">
	<li>
	<figure class="meal-photo">
		<img src="http://www.alwaha.pk/wp-content/uploads/2017/11/greek-salad.jpg">
	</figure>
	</li>
	<li>
	<figure class="meal-photo">
		<img src="https://www.seriouseats.com/recipes/images/2016/03/20160201-seafood-salad-vicky-wasik-17-1500x1125.jpg">
	</figure>
	</li>
	<li>
	<figure class="meal-photo">
		<img src="https://cdn-image.myrecipes.com/sites/default/files/styles/medium_2x/public/image/recipes/ck/08/10/fish-soup-ck-1842315-x.jpg?itok=JKRQyDDI">
	</figure>
	</li>
	<li>
	<figure class="meal-photo">
		<img src="https://cdn-image.foodandwine.com/sites/default/files/styles/medium_2x/public/linguine-with-seafood-sauce-xl-200202.jpg?itok=8lgI6Yxb">
	</figure>
	</li>
	<li>
	<figure class="meal-photo">
		<img src="http://sisijemimah.com/wp-content/uploads/2016/04/Spicy-grilled-fish.jpg">
	</figure>
	</li>
	<li>
	<figure class="meal-photo">
		<img src="https://therecipecritic.com/wp-content/uploads/2016/06/spicylimeshrimpcrop.jpg">
	</figure>
	</li>
	<li>
	<figure class="meal-photo">
		<img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/pasta-salad-horizontal-jpg-1522265695.jpg">
	</figure>
	</li>
	<li>
	<figure class="meal-photo">
		<img src="https://static.independent.co.uk/s3fs-public/thumbnails/image/2016/09/22/12/wine.jpg">
	</figure>
	</li>
  </ul>
  </section>
  
  <section class="mobile">
  <h3 class="text-center">SI TE BENI REZERVIMIN</h3>
  <div class="container">
	<div class="row">
	<div class="col-md-6">
		<div class="text">
			<input type="text" placeholder="Emri" class="form-control"><br>
			<input type="text" placeholder="Numri i personave" class="form-control"><br>
			<textarea class="form-control" rows="8" placeholder="Preferenca"></textarea>
			<button class="btn btn-warning btn btn-block">Rezervo</button>
			
		</div>
	</div>
	<div class="col-md-6">
	<div class="works-step">
		<div>1</div>
		<p>
		Shkruaj emrin nen te cilin behet rezervimi
		</p>
		<div>2</div>
		<p>
		Shkruaj numrin e personave ose numrin e tavolinave qe do te rezervoni
		</p>
		<div>3</div>
		<p>
		Shkruaj kerkesa ose preferenca te mundshme
		</p>
		<div>4</div>
		<p>
		Per prenotime, na kontaktoni ne numrin tone te telefonit ose ne rrjetet tona sociale
		</p>
		<a href=""><img src="https://shopily.s3.amazonaws.com/uploads/stores/1973/app-store-coupon-my-new.png"></a>
		<a href=""><img src="https://gutschurch.com/wp-content/uploads/2018/09/download-google-play-store-logo.png"></a>
		
	</div>
  </section>
  <section class="cities">
	<h3 class="text-center">Galeria</h3>
	
	<div class="container">
		<div class="row">
			<div class="col-md-3">
				<img src="https://lh3.googleusercontent.com/p/AF1QipM6rv-cCsOjmZFsdxK8Go8H1NzUyEQBOyCsuFDO=s1600-w1600">
			</div>
			<div class="col-md-3">
				<img src="https://fastly.4sqi.net/img/general/200x200/9833332_YwTMR14loeqSw9wKcOULYr8naAq9-uB6Y5yTmlXlpJs.jpg">
			</div>
			<div class="col-md-3">
				<img src="http://www.lagoonseafood.com/wp-content/uploads/2016/10/fresh-fish-on-ice.jpg">
			</div>
			<div class="col-md-3">
				<img src="https://images.britcdn.com/wp-content/uploads/2014/08/mussels101-645x659.jpg?w=1000&auto=format">
			</div>
			<div class="col-md-3">
				<img src="http://www.ricenflour.com/wp-content/uploads/2016/06/IMG_8580-002-770x440.jpg">
			</div>
			<div class="col-md-3">
				<img src="https://cdn0.wideopeneats.com/wp-content/uploads/2016/12/days-order-seafood-restaurant.png">
			</div>
			<div class="col-md-3">
				<img src="https://www.virginexperiencedays.co.uk/content/img/product/large/luxury-wine-tasting-paired-04162749.jpg">
			</div>
			<div class="col-md-3">
				<img src="https://www.facebook.com/images/fb_icon_325x325.png">
				<p>For more images, visit our facebook page...
			</div>
		</div>
	</div>
  </section>
  
  <section class="testimonials">
	<h3 class="text-center">DISA FJALE NGA NE</h3>
		<div class="container">
			<div class="row">
				
				<div class="col-md-4">
					
						<p>
						who is such a man as does not want to get success life is not meant for work
						who is such a man as does not want to get success life is not meant for work
						who is such a man as does not want to get success life is not meant for work
						who is such a man as does not want to get success life is not meant for work
						</p>
						<cite><img src="https://www.allaboutalbania.eu/images/directory/business/big_26910968.578577135817434.4669722003618537983.o_cxqvaye2.jpg">Eduard Kacadej</cite>
					
				</div>
				
				
				<div class="col-md-4">
					
						<p>
						who is such a man as does not want to get success life is not meant for work
						who is such a man as does not want to get success life is not meant for work
						who is such a man as does not want to get success life is not meant for work
						who is such a man as does not want to get success life is not meant for work
						</p>
						<cite><img src="https://www.xing.com/image/7_d_2_99d9ec4a1_31748927_1/tresi-kacadej-foto.1024x1024.jpg">Tresi Kacadej</cite>
					
				</div>
				
				
				<div class="col-md-4">
					
						<p>
						who is such a man as does not want to get success life is not meant for work
						who is such a man as does not want to get success life is not meant for work
						who is such a man as does not want to get success life is not meant for work
						who is such a man as does not want to get success life is not meant for work
						</p>
						<cite><img src="https://3.bp.blogspot.com/-wNzV7m7XFaY/WDy0kQXhiFI/AAAAAAAAAE4/co7xZnQFtCMPNfn514KuFoWMbhYJxE18gCLcB/s400/Donald%2BTrump.jpg">Arlind Kacadej</cite>
					
				</div>
			</div>
		</div>
  </section>
  <section class="form">
	<div class="container">
		<h3 class="text-center">JEMI TE LUMTUR NESE DEGJOJME ME SHUME PREJ JUSH</h3>
	</div>
	<div class="row gap">
		<div class="col-md-4">
			<input type="text" placeholder="Emri" class="form-control"><br>
			<input type="text" placeholder="Email" class="form-control"><br>
			<!––<input type="password" placeholder="Fjalekalim" class="form-control">––>
		</div>
		<div class="col-md-8">
			<textarea class="form-control" rows="8" placeholder="koment"></textarea>
			<button class="btn btn-warning btn btn-block">Dergo</button>
		</div>
	</div>
  </section>
</body>
</html>
