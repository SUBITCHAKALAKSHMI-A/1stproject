# 1stproject
DOCTYPE html>
<html>
<head>
    <title>Fresh harvest Mart</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width initial-scale=1.0">
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
   <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    <style>
        img{
            height:120px;
            width:120px;
        }
        em{
            color:rgb(0, 102, 128);
            text-align:center;
            font-family:cursive;
            font: 50px;
        }
        column{
            flex:50%;
            padding: 0 4px;
            max-width:100%;
            max-height:100%;
            box-shadow: 10px 10px;
        }
        .block{
            width: 100%;
            height: 100%;
            box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        }
        .topnav {
  width: 100%;
  background-color: #555;
  overflow: auto;
}

.topnav a {
  float: left;
  width: 14%;
  text-align: center;
  padding: 10px 0;
  transition: all 0.3s ease;
  color: white;
  font-size: 30px;
}

.topnav a:hover {
  background-color: #000000;

}
.active {
  background-color: #971d56;
}
.auto
{
  width: auto;
  height: auto;
}
.carousel-inner > .item > img {
   width:640px;
   height:360px;
 }
        </style>

</head>
<body>
    <header>
        <div class="container-fluid bg-warning">
            <nav class="navbar navbar-expand-lg">
            <div class="image"><img src="data:image/png;base64,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" >&nbsp;<em class="text-responsive">let be live healthy with fresh harveset</em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            </div>  
           <div clas="img-fluid"><img src="https://t3.ftcdn.net/jpg/03/11/87/52/360_F_311875255_d57wDCwlZxdtOEwsnmXLHkV1r29i1R2U.jpg" class="rounded-circle" >
            <img src="https://cdn.dribbble.com/userupload/5406028/file/original-3126394fefe5a8e29d77870d405dc54f.jpg?resize=400x300&vertical" class="rounded-circle">
            <img src="https://cdn5.vectorstock.com/i/1000x1000/86/59/cherry-juice-fresh-fruit-3d-icon-vector-20428659.jpg" class="rounded-circle float-end"></div>      
          <h1 class="text-responsive" style="text-align:right; font-weight:bold; font-family:Sofia,sans-serif">Shop in fresh harvest</h1>
        </div>   
        </nav>
        </div>
        <div class="topnav">
            <a class="active" href="#home">Home</a> 
            <a href="#Exotic fruits">Exotic fruits</a> 
            <a href="#Daires">Daires</a>  
            <a href="#Beauty care">Beauty care</a>
            <a href="#Home appliances">Home appliances</a>
            <a href="#Stationary">Stationray</a>
            <a href="#Style wears">Style wears</a>
          </div>
          
           <div class="carousel slide" data-bs-ride="carousel" id="demo">
              <div class="carousel-indicators">
              <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button> 
              <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
              <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
              <button type="button" data-bs-target="#demo"  data-bs-slide-to="3"></button>
              </div>
          
          <div class="carousel-inner">
            <div class="carousel-item ">
              <img src="https://assets.indiadesire.com/images/flipkart%20watch%20fest.jpg" alt="dog" class="img-thumbnail d-block" style="height: auto; width: 100%;" >
            </div>
            <div class="carousel-item active" >
              <img src="https://d4t7t8y8xqo0t.cloudfront.net/resized/750X277/pages%2F768%2Fimage20191022055104.jpg" alt="egg" class="img-thumbnail d-block" style="height: auto; width: 100%;">
            </div>
            <div class="carousel-item">
              <img src="https://lavichebathessentials.com/cdn/shop/files/1_v2_5bb91a97-5d66-4af7-9ea0-6ae8b3a1fd1c.jpg?v=1700489254" alt="rat" class="img-thumbnail d-block" style="height: auto; width:100%;">
            </div>
            <div class="carousel-item">
              <img src="https://images-eu.ssl-images-amazon.com/images/G/40/UAE-hq/2022/img/Shoes/XCM_Manual_1460119_4934491_750x300_2X.jpg" alt="cat" class="img-thumbnail d-block" style="height: auto;width: 100%;">
            </div>
          </div>
          <button type="button" class="carousel-control-prev"  data-bs-slide="prev" data-bs-target="#demo">
            <span class="carousel-control-prev-icon"></span>  
          </button>
          <button type="button" class="carousel-control-next" data-bs-slide="next" data-bs-target="#demo">
            <span class="carousel-control-next-icon"></span>
          </button>
        </div>
        <div class="container-fluid mt-3">
        <div >
          <div class="row m-3 bg-light">
             <div class="col-4 p-5"><img class="block " src="https://c4.wallpaperflare.com/wallpaper/742/963/615/vegetables-basket-green-background-garden-wallpaper-preview.jpg" alt="abc" class="img-thumbnail" >
            <h4 style="text-align: center;text-transform: uppercase; font-weight:bold;padding-top: 20px; color: white;
            text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;"> exotic vegetables </h4>
        </div>
             <div class="col-4 p-5"><img class="block" src="https://img.freepik.com/premium-photo/ripe-fruits-with-splashes-juice_372999-9344.jpg" alt="def" class="img-thumbnail"  >
             <h4 style="text-align: center;text-transform: uppercase; font-weight:bold;padding-top: 20px; color: white;
            text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;"> fresh fruits </h4></div>
             <div class="col-4 p-5"><img class="block" src="https://c4.wallpaperflare.com/wallpaper/476/843/740/food-canned-fruit-cans-tomato-cucumber-onion-assorted-fruits-and-vegetables-in-glass-containers-wallpaper-preview.jpg" alt="subi" class="img-thumbnail" >
             <h4 style="text-align: center;text-transform: uppercase; font-weight:bold;padding-top: 20px; color: white;
             text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;"> daily staple </h4></div>
            </div>
        
    
                    <div class="row m-3 bg-light ">
                        <div class="col-4 p-5"><img class="block"  src="https://t3.ftcdn.net/jpg/06/17/77/38/240_F_617773813_5Oxtk1QTf9YylBam0a1NyYFaVdGrMjcb.jpg" alt="fog" class="img-fluid img-thumbnail"width="100" height="100" >
                        <h4 style="text-align: center;text-transform: uppercase; font-weight:bold;padding-top: 20px; color: white;
                        text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;"> dessert </h4></div>
                        <div class="col-4 p-5"><img class="block"  src="https://c4.wallpaperflare.com/wallpaper/528/52/56/cakes-desserts-tarts-sweet-wallpaper-preview.jpg" class="img-fluid img-thumbnail" width="100" height="100">
                        <h4 style="text-align: center;text-transform: uppercase; font-weight:bold;padding-top: 20px; color: white;
                        text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;"> cakes</h4></div>
                        <div class="col-4 p-5"><img class="block"  src="https://img.freepik.com/premium-photo/ice-cream-with-variety-colorful-tempting-toppings-ai-generated_859483-12437.jpg" class="img-thumbnail img-fluid" width="100" height="100">
                        <h4 style="text-align: center;text-transform: uppercase; font-weight:bold;padding-top: 20px; color: white;
                        text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;"> ice cream </h4></div>
                    </div>
               
                <div class="row m-3 bg-light">
                    <div class="col-4 p-5"><img class="block" src="https://c0.wallpaperflare.com/preview/662/589/208/united-kingdom-brighton-shampoo-redken.jpg" class="img-fluid img-thumbnail"width="100" height="100" >
                    <h4 style="text-align: center;text-transform: uppercase; font-weight:bold;padding-top: 20px; color: white;
                        text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;"> shampoo </h4></div>
                    <div class="col-4 p-5"><img class="block" src="https://e0.pxfuel.com/wallpapers/104/923/desktop-wallpaper-pink-spa-candle-soap-bath-salts-towel.jpg" class="img-fluid img-thumbnail" width="100" height="100">
                    <h4 style="text-align: center;text-transform: uppercase; font-weight:bold;padding-top: 20px; color: white;
                    text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;"> cleaning & household </h4></div>
                    <div class="col-4 p-5"><img class="block" src="https://images.pexels.com/photos/267301/pexels-photo-267301.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" class="img-fluid img-thumbnail" width="100" height="100">
                    <h4 style="text-align: center;text-transform: uppercase; font-weight:bold;padding-top: 20px; color: white;
                    text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;"> sandles and shoes</h4></div>
        </div>
        <div class="row m-3 bg-light ">
          <div class="col-3 p-4"><img src="https://images.meesho.com/images/products/146498993/eahxo_512.webp" class="rounded-circle img-fluid"></div>
       <div class="col-3 p-4"><img src="https://www.allthingsaboutwedding.com/wp-content/uploads/2022/03/Royal-Blue-Jacquard-Silk-Festival-Wear-Half-Lehenga-Saree-AllThingsAboutWedding-1.jpeg" class="rounded-circle img-fluid"></div>
       <div class="col-3 p-4"><img  src="https://www.rehmatboutique.net/wp-content/uploads/2023/08/cord-set-rayon-western-wear-sale-offer-5280a-746.jpg" class="rounded-circle img-fluid"></div>
       <div class="col-3 p-4"><img src="https://www.textileinfomedia.com/img/cgca/girls-western-short-shirt-full.jpg" class="rounded-circle img-fluid"></div></div>
       <div class="row m-2 bg-light ">
        <div class="col-3 p-4"><img src="https://images.meesho.com/images/products/188465208/2tuya_512.webp" class="rounded-circle img-fluid"></div>>
        <div class="col-3 p-4"><img src="https://rukminim2.flixcart.com/image/832/832/xif0q/backpack/v/6/j/-original-imagz87k72ygwfzn.jpeg?q=70" class="rounded-circle img-fluid"></div>
          <div class="col-3 p-4"><img src="https://rukminim2.flixcart.com/image/832/832/xif0q/suitcase/f/d/0/67-8-wheel-trolley-bag-set-of-2-small-medium-size-black-color-original-imagq45bzz2sfxeb.jpeg?q=70" class="rounded-circle img-fluid"></div>
            <div class="col-3 p-4"><img src="https://m.media-amazon.com/images/I/71DD4zXNNSL._SX695_.jpg" class="rounded-circle img-fluid"></div></div>
      </header>
      <p style="text-align: center;">Sell perosonlized recommendations<br>
        <button>Sign in</button><br>
        New customer&nbsp;<a href="www.google.com" style="text-decoration: none ;">start here</a></p><hr>
        <div class="container-fluid bg-secondary"><br>
          <p style="text-align: center;"><b>Back To Top</b></p><br><br>
        <div class="container mt-3">
           <div class="row">
            <div class="col-sm-3 p-3 bg-secondary text-dark"><h4><b>Get to know us</b></h4>
            <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">About us</a><br>
            <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Careers</a><br>
            <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Press Realeases</a><br>
            <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">fresh harvest Science</a>
          </div>
            <div class="col-sm-3 p-3 bg-secondary text-Dark"><h4><b>Connect with us</b></h4>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Facebook</a><br>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Instagram</a><br>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Twitter</a><br>
              
            </div>
            <div class="col-sm-3 p-3 bg-secondary text-Dark"><h4><b>Make Money with us</b></h4>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Sell on fresh harvest</a><br>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Sell under fresh harvest Accelerator</a><br>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">protect and Build your Brand</a><br>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">fresh harvest Globl Selling</a><br>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Become an Affiliate</a><br>
            <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Fulfilment by fresh harvest</a><br>
            <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Advertise your products</a><br>
            <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">fresh harvest pay on Merchants</a>
              </div>
            <div class="col-sm-3 p-3 bg-secondary text-dark"><h4><b>Let Us Help You</b></h4>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">COVID-19 and fresh harvest</a><br>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Your Account</a><br>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Return Center</a><br>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">100% purchase protection</a><br>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">fresh harvest App Download</a><br>
              <a href="www.googlr.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Help</a>
              </div>
          </div>
        
            <div class="row">
              <div class="col-sm-8 p-3 bg-secondary text-dark"><a class="navbar-brand" href="www.amazon.in"> <img src="https://yt3.googleusercontent.com/ytc/AIf8zZS1CGnAtd8L1QEKkr_xHyR03-X8_KQyyWSFsB7G=s900-c-k-c0x00ffffff-no-rj" height="70" width="100">.in</a></div>
              <div class="col-sm-4 p-3 bg-secondary text-dark">
                <i style="font-size:24px" class="fa">&#xf0ac;</i>
                <select>
                <option style="font-size:24px"> <i class="fa fa-globe">English</i></option>
                <option style="font-size:24px"> <i class="fa fa-globe">Tamil</i></option>
                <option style="font-size:24px"> <i class="fa fa-globe">French</i></option>
                <option style="font-size:24px"> <i class="fa fa-globe">Japanese</i></option>
                </select>
              </div>
            </div>
          <div class="row">
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Austrila</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Canada</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Brazil</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none;-webkit-text-fill-color: #bdcfc9;">China</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">France</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Germany</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Italy</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Japan</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Mexico</a></h6></div><br>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Netherlands</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Poland</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Singapore</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Spain</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Turkey</a></h6></div>
            <div class="col p-3 bg-secondary text-Dark"><h6><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Europe</a></h6></div>
             </div>
        </div>
        </div>
        </div>
        <div class="container-fluid bg-dark">
          <div class="container">
            <div class="row">
              <div class="col-sm-3 p-3 bg-dark text-white"><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">AbeBooks</a><br>
              <a href="www.google.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Books<br> arts & collections</a></div>
              <div class="col-sm-3 p-3 bg-dark text-white"><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">fresh harvest Web Service</a><br>
                <a href="www.google.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Scalable cloud<br>Computer service
                </a></div>
              <div class="col-sm-3 p-3 bg-dark text-white"><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Audibile</a><br>
                <a href="www.google.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Download<br>Audio Books</a></div>
              <div class="col-sm-3 p-3 bg-dark text-white"><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">IMDb</a><br>
                <a href="www.google.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Movies,TV<br>&Celebrities</a></div>
            </div><br>
          </div>
          <p style="text-align: center;"><a href="www.google.com " style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Conditions of use and scale</a>
            &nbsp;&nbsp;&nbsp;&nbsp;<a href="www.goolge.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Privacy policy</a>  &nbsp;&nbsp;&nbsp;&nbsp;
          <a href="Www.google.com" style="text-decoration: none; -webkit-text-fill-color: #bdcfc9;">Interest- based ads<br>
            <i class="fa fa-copyright" aria-hidden="true"></i>1996-2023,fresh harvest.com,Inc or its affilicates
          </p>
        
        </div>
        </body>
        </html>
  
  </body>
  </html>
