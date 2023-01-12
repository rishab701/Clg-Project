<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Project</title>
    <style>
        html{
            height:1000px;
        }
        #dive{
           font-size:20px;
           height:15px;
           font-style: italic;
        }
        .div1{
            display:flex;
            align-items: center;
            justify-content: center;
            background-color: blue;
            height:50px;
            width:1500px;
            position:fixed;
        }
        .divs{
           color:white;
           padding:30px;
           font-weight: bold;
        }
        input[type="text"]{
            height:25px;
            width:530px;
        }
        button{
            height:30px;
            width:130px;
            background-color: white;
            border:2px solid white;
            color:blue;
        }
        .div2{
            display:flex;
            justify-content: center;
            align-items: center;
            padding-top:45px;
            padding-bottom:0px;
        }
        img{
            height:70px;
        }
        .src1{
            padding:20px;
        }
        p{
            font-weight:bolder;
        }
        .idea p{
            text-align:center;
            
        }
        #id1 img{
            width:1500px;
            height:300px;
        }
        .view{
            display:grid;
            grid-template-columns: auto auto auto auto auto;
            padding-top:50px;
            border:2px solid whitesmoke;
        }
        .g img{
            width:20px;
            height:20px;
        }
        .g{
            display:flex;
            align-items:center;
            justify-content:center;
        }
        .idea{
            font-size:30px;
            text-align:center;
        }
        .btn{
            background-color:blue;
            color:white;
            width:80px;
            height:50px;
              
        }
        .src3{
            width:200px;
            height:180px;
        }
        .p1{
            font-weight: lighter;
            color:grey;
        }
        .p{
            font-weight: lighter;
            color:green;
        }
        .p2{
            font-weight: lighter;
        }
        .class{
            color:grey;
            padding-left:10px;
            padding-right:10px;
        }
        .body{
            font-weight: lighter;
            font-size:12px;
            color:grey;
            padding-left:10px;
            padding-right:10px;
        }
        .sec{
            padding-top:20px;
        }
        .class1{
            padding-left:10px;
            padding-right:10px;
        }
        .body6{
            font-weight: lighter;
            font-size:12px;
            color:grey;
            padding-left:10px;
            padding-right:10px;
            padding-bottom:30px;
        }
        li{
            list-style:none;
            color:white;
            font-size:13px;
        }
        .footer{
            height:220px;
            padding-top:20px;
            background-color:rgb(11, 16, 59);
            display:grid;
            grid-template-columns: auto auto auto auto auto auto;
            border-bottom:2px solid grey;
        }
        .foot{
            font-weight: bolder;
            color:grey;
            padding-left:40px;
        }
        #cl{
            padding-left:60px;
        }
        #cl1{
            padding-left:20px;
        }
        .end{
            background-color: rgb(11, 16, 59);;
            display:flex;
            justify-content: center;
        }
        .end1{
            padding:30px;
        }
        .a{
            font-weight: lighter;
            font-size: 20px;
            color:white;
        }
        .b{
            border-left: 2px solid grey;
        }
        .i{
            text-align:center;
        }
        #i1{
            padding-left:100px;
        }
    </style>
</head>
<body>
    <div class="div1">
        <div class="divs" id="dive">Shopify</div>
        <div class="divs">
             <input type="text" placeholder="Search for products, brands and more">
        </div>
        <div class="divs">
            <button>Login</button>
        </div>
        <div class="divs">Become a Seller</div>
        <div class="divs">More</div>
        <div class="divs">Cart</div>
    </div>
    
    <div class="div2">
        <div class="src1">
              <img src="https://rukminim1.flixcart.com/flap/128/128/image/29327f40e9c4d26b.png?q=100">
              <p>Grocery</p>
        </div>
        <div class="src1">
              <img src="https://rukminim1.flixcart.com/flap/128/128/image/22fddf3c7da4c4f4.png?q=100">
              <p>Mobiles</p>
        </div>
        <div class="src1">
              <img src="https://rukminim1.flixcart.com/flap/128/128/image/c12afc017e6f24cb.png?q=100">
              <p>Fashion</p>
        </div>
        <div class="src1">
              <img src="https://rukminim1.flixcart.com/flap/128/128/image/69c6589653afdb9a.png?q=100">
              <p>Electronics</p>
        </div>
        <div class="src1">
              <img src="https://rukminim1.flixcart.com/flap/128/128/image/ab7e2b022a4587dd.jpg?q=100">
              <p>Home</p>
        </div>
        <div class="src1">
              <img src="https://rukminim1.flixcart.com/flap/128/128/image/0ff199d1bd27eb98.png?q=100">
              <p>Appliances</p>
        </div>
        <div class="src1">
              <img src="https://rukminim1.flixcart.com/flap/128/128/image/71050627a56b4693.png?q=100">
              <p>Travel</p>
        </div>
        <div class="src1">
              <img src="https://rukminim1.flixcart.com/flap/128/128/image/f15c02bfeb02d15d.png?q=100">
              <p>Top Offers</p>
        </div>
        <div class="src1">
              <img src="https://rukminim1.flixcart.com/flap/128/128/image/dff3f7adcf3a90c6.png?q=100">
              <p>Beauty,Toys and more</p>
        </div>
        <div class="src1">
              <img src="https://rukminim1.flixcart.com/fk-p-flap/128/128/image/05d708653beff580.png?q=100">
              <p>Two wheelers</p>
        </div>
    </div>
    <hr>
    <div>
        <div id="id1">
            <img src="https://www.bigbasket.com/media/uploads/banner_images/YXHP144_hp_fom_m_bbpl-staples_460_121222_Bangalore.jpg">
        </div>
    </div>

    <div class="view">
        <div class="gap">
            <p class="idea">Best of Electronics
                <br>
                <br>
                <button class="btn">View All</button>
            </p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/kmp7ngw0/monitor/j/z/h/s2721hn-27-py0df-dell-original-imagfjphuywuh2a7.jpeg?q=70">
            <br>
            <br>
            <br>
            <p class="p2">Monitor</p>
            <p class="p">From Rs8279/-</p>
            <p class="p1">DELL</p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/kokdci80/dslr-camera/v/e/x/z-24-200mm-z5-nikon-original-imag2zuekuxgxsgg.jpeg?q=70">
            <br>
            <br>
            <br>
            <p class="p2">Top Mirrorless Cameras</p>
            <p class="p">Shop Now!</p>
            <p class="p1">Canon, Sony, Fujifilm</p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/printer/j/j/y/hp-laserjet-m1005-multifunction-original-imadxhzpeb9qbrfg.jpeg?q=70">
            <br>
            <br>
            <br>
            <p class="p2">Printers</p>
            <p class="p">From Rs3299/-</p>
            <p class="p1">HP</p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/kge0n0w0/projector/m/q/3/i9-classsic-hd-720p-8908012116066-egate-original-imafwnfzxqp3yymc.jpeg?q=70">
            <br>
            <br>
            <br>
            <p class="p2">Projector</p>
            <p class="p">From Rs6299/-</p>
            <p class="p1">Egate</p>
        </div>
    </div>
    <div class="view">
        <div class="gap">
            <p class="idea">Sweet
                <p class="i">
                <button class="btn">View All</button>
            </p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=50,metadata=none,w=180/app/images/products/sliding_image/37178a.jpg?ts=1660640241">
            <br>
            <br>
            <br>
            <p class="p2">Nestle Classic Milk Chocolate</p>
            <p class="p">Quantity: 34g</p>
            <p class="p1">Rs20</p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=50,metadata=none,w=180/app/images/products/sliding_image/496297a.jpg">
            <br>
            <br>
            <br>
            <p class="p2">Nestle Munch Max Coated Wafer Chocolate</p>
            <p class="p">Quantity: 42g</p>
            <p class="p1">Rs 20</p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=50,metadata=none,w=180/app/images/products/sliding_image/16779a.jpg?ts=1661235854">
            <br>
            <br>
            <br>
            <p class="p2">Kinder Joy Shaped Chocolates</p>
            <p class="p">Quantity: 20g</p>
            <p class="p1">Rs 45</p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=50,metadata=none,w=180/app/images/products/sliding_image/476412a.jpg">
            <br>
            <br>
            <br>
            <p class="p2">Cadbury Drinking Chocolate</p>
            <p class="p">Quantity: 500g</p>
            <p class="p1">Rs 695</p>
        </div>
    </div>
    <div class="view">
        <div class="gap">
            <p class="idea">Snacks & Munchies
                <p class="i">
                <button class="btn">View All</button>
            </p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/104616a.jpg?ts=1662018947">
            <br>
            <br>
            <br>
            <p class="p2">Haldiram's Pudina Treat Chips</p>
            <p class="p">Quantity: 55g</p>
            <p class="p1">Rs25</p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/446729a.jpg?ts=1657110830">
            <br>
            <br>
            <br>
            <p class="p2">Haldiram's Snack Lite</p>
            <p class="p">Quantity: 85g</p>
            <p class="p1">Rs 25</p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/482828a.jpg">
            <br>
            <br>
            <br>
            <p class="p2">Haldiram's Takatak Chatpata Masala Sticks</p>
            <p class="p">Quantity: 105g</p>
            <p class="p1">Rs 25</p>
        </div>
        <div class="gap">
            <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/447334a.jpg?ts=1661398846">
            <br>
            <br>
            <br>
            <p class="p2">Too Yumm Baked Potato Stix Crisps</p>
            <p class="p">Quantity: 70g</p>
            <p class="p1">Rs 35</p>
        </div>
    </div>
    <div class="view">
        <div class="gap">
            <p class="idea">Beauty,Food</p>
              <p class="idea">Toys and more</p>
                <br>
                <p class="i">
                <button class="btn">View All</button>
            </p>
        </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/kzzw5u80/coffee/s/b/x/-original-imagbwf3wvhzfh5z.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Coffee Powder</p>
        <p class="p">Upto 80% off</p>
        <p class="p1">Nescafe,continental & More</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/j3xbzww0/face-wash/4/4/s/150-purifying-neem-face-wash-himalaya-original-imaeuyfzgdmythzw.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Skin Care</p>
        <p class="p">Upto 40% off</p>
        <p class="p1">Himalaya,MamaEarth & More</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/kz5vwy80/helmet/o/4/k/-original-imagb8azfdthjhqr.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Rider Helmets</p>
        <p class="p">From 699</p>
        <p class="p1">Vega,Steelbird & More</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/kjuby4w0/deodorant/v/c/d/400-one8-intense-fresh-deo-pack-of-2-200ml-x-2-2-perfume-body-original-imafzbn4nv2zhccp.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Deodrants and Perfumes</p>
        <p class="p">Upto 60% off</p>
        <p class="p1">Denver,Fog & More</p>
    </div>
</div>
<div class="view">
    <div class="gap">
        <p class="idea">Cold Drinks &</p>
            <p class="idea">Juices</p>
            <br>
            <p id="i1">
            <button class="btn">View All</button>
        </p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/447733a.jpg">
        <br>
        <br>
        <br>
        <p class="p2">Pepsi Soft Drink</p>
        <p class="p">600 ml</p>
        <p class="p1">Rs 38</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/314a.jpg?ts=1657699524">
        <br>
        <br>
        <br>
        <p class="p2">Thums Up Soft Drink</p>
        <p class="p">750 ml</p>
        <p class="p1">Rs 38</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/312a.jpg?ts=1657699693">
        <br>
        <br>
        <br>
        <p class="p2">Sprite Lime Flavored Soft Drink</p>
        <p class="p">750 ml</p>
        <p class="p1">Rs 38</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/386a.jpg?ts=1667219215">
        <br>
        <br>
        <br>
        <p class="p2">Red Bull Sugar Free Energy Drink</p>
        <p class="p">250 ml</p>
        <p class="p1">Rs 125</p>
    </div>
</div>
<div class="view">
    <div class="gap">
        <p class="idea">Sports Healthcare & </p>
            <p class="idea">More</p>
            <br>
            <p id="i1">
            <button class="btn">View All</button>
        </p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/k3j1z0w0/kit/d/v/e/combo-of-ab-wheel-rollerand-tummy-trimmer-exercisee1s-charuvi-original-imafdwh9nyzyujvk.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Ab Exerciser</p>
        <p class="p">From Rs199/-</p>
        <p class="p1">Adrenex,Manogyam & More</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/light/h/9/h/imported-bicycle-rear-light-5-led-usb-rechargeable-waterproof-original-imaeq7hj3gppgcxz.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Cycle Accesiories</p>
        <p class="p">From Rs125</p>
        <p class="p1">Best Deals</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/l51d30w0/shopsy-sport-mat/p/w/s/anadi-01-yoga-mat-4-30-anadi-enterprise-15-original-imagfsxudxcm7r48.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Yoga Mat</p>
        <p class="p">From Rs 165</p>
        <p class="p1">beatXP,HRX & Adrenex</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/kkimfm80/tea/z/n/1/premium-pouch-regular-tea-powder-tata-original-imafzuf2mnubzphd.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Tea powder</p>
        <p class="p">Upto 75% Off</p>
        <p class="p1">Tata,Lipton & More</p>
    </div>
</div>
<div class="view">
    <div class="gap">
        <p class="idea">Fashion Top
            <p class="idea">Deals</p>
            <br>
            <p class="i">
            <button class="btn">View All</button>
        </p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/fk-p-flap/200/200/image/5aa98b7cee183286.jpg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Best selling Styles</p>
        <p class="p">Min. 40% Off</p>
        <p class="p1">Woodland,U.S. Polo Assn...</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/k0mqtu80/shoe/u/p/n/indi-exclusive-12-levi-s-navy-blue-original-imafke6bmczzkfxh.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Levi's, Flying Machine & More</p>
        <p class="p">Min. 50% Off</p>
        <p class="p1">Men's Sneakers..</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/kz8qsnk0/lehenga-choli/m/k/z/free-3-4-sleeve-puspar-lh-001-divastri-original-imagbarzwpevcr5e.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Lehenga Cholis & Gowns</p>
        <p class="p">Buy 3, Get 10% Off</p>
        <p class="p1">Buy 2, Get 5% Off</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/kxnl6kw0/jewellery-set/a/c/d/na-na-m11-single-r5-bright-style-original-imaga2ahezaabmry.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Fashion Jewellery</p>
        <p class="p">From Rs99</p>
        <p class="p1">Best Deals!</p>
    </div>
</div>
<div class="view">
    <div class="gap">
        <p class="idea">Fresh Vegetables
            <br>
            <p class="i">
            <button class="btn">View All</button>
            </p>
        </p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/199435a.jpg?ts=1638183410">
        <br>
        <br>
        <br>
        <p class="p2">New Potato(Aloo)</p>
        <p class="p">1 kg</p>
        <p class="p1">Rs 21</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/391306a.jpg?ts=1652789363">
        <br>
        <br>
        <br>
        <p class="p2">Onion(Pyaz)</p>
        <p class="p">1 kg</p>
        <p class="p1">Rs 37</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/3881a.jpg?ts=1671620195">
        <br>
        <br>
        <br>
        <p class="p2">Hybrid Tomato(Tamatar)</p>
        <p class="p">500 g</p>
        <p class="p1">Rs 13</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://cdn.grofers.com/cdn-cgi/image/f=auto,fit=scale-down,q=85,metadata=none,w=250,h=250/app/images/products/sliding_image/17748a.jpg?ts=1650869772">
        <br>
        <br>
        <br>
        <p class="p2">Lemon(Nimbu)</p>
        <p class="p">6 pieces (150 g - 200 g)</p>
        <p class="p1">Rs 19</p>
    </div>
</div>
<div class="view">
    <div class="gap">
        <p class="idea">Top Deals
            <p class="i">
            <button class="btn">View All</button>
        </p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/ktop5e80/tablet/x/9/o/mk2k3hn-a-apple-original-imag6yy7xjjugz4w.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Apple iPads</p>
        <p class="p">Shop Now!</p>
        <p class="p1">Liquid Retina Display</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/l5jxt3k0/dslr-camera/m/n/a/-original-imagg7hsggshhwbz.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Mirrorless Cameras</p>
        <p class="p">From Rs57,999</p>
        <p class="p1">NCEMI | Product Exch</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/xif0q/projector/w/s/d/zeb-pixaplay-10-led-projector-with-full-hd-1080p-and-built-in-original-imaggvt439wgm26g.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Exciting New Launches</p>
        <p class="p">From Rs8499</p>
        <p class="p1">Samsung, Canon & more</p>
    </div>
    <div class="gap">
        <img class ="src3" src="https://rukminim1.flixcart.com/image/200/200/kzsqykw0/mobile-camera-lens-protector/p/g/v/yes-cp-12-zoy-original-imagbqghwbumu4qj.jpeg?q=70">
        <br>
        <br>
        <br>
        <p class="p2">Camera Lens Protector</p>
        <p class="p">From Rs99</p>
        <p class="p1">For All Top Models</p>
    </div>
</div>
<div class="sec">
    <div>
        <p class="class1">Top Stories : Brand Directory</p>
    </div>
    <div>
        <p class="class">MOST SEARCHED FOR ON SHOPIFY: </p>
        <p class="body">Shopify Axis Bank Super Elite Credit card | Bounce Infinity E1 | Buy Laptop on EMI | vivo T1X | OPPO Reno8 5G | OPPO Reno8 Pro 5G | Nothing Phone 1 | Sell Old Mobile Phones | ASUS TUF Gaming F15 Core i5 10th Gen | Electronics Store | OPPO A16K | Vivo Y33T | OPPO Reno7 5G | Bathroom Exhaust Fan | Samsung Window AC | OPPO Reno7 Pro 5G | iPhone 13 | iPhone 13 Pro | iPhone 13 Pro Max | iPhone 13 Mini | Google Pixel 6a covers | Flipkart Quick | Books | Shopify Help Centre | Online Boat Store | Covers from Rs 99 | Shopify Track Orders | Shopify Manage Orders | Shopify Return Orders | Shopify Gift Cards Store | Shopify Axis Bank Credit Card | Shopify Pay Later</p>
    </div>
    <div>
        <p class="class">COLD DRINKS AND JUICES: </p>
        <p class="body">Pepsi Soft Drink | Mountain Dew Soft Drink  | Pepsi Swag Soft Drink | Coca-Cola Soft Drink | 7UP Soft Drink | Sprite Lime Flavored Soft Drink | Pepsi Black Zero Sugar Soft Drink | Real Fruit Power Cranberry Juice | Maaza Mango Drink 1.2 | Real Fruit Power Mixed Fruit Juice | Real Fruit Power Pineapple Juice | Frooti Mango Drink | Real Activ 100% Orange Juice | Real Activ Coconut Water | Real Fruit Power Coconut Water | Real Activ 100% Apple Juice | Real Activ 100% Mixed Fruit Juice | Real Fruit Power Cocunut Water| Tropicana 100% Mixed Fruit Juice| Hershey's Chocolate Syrup | Hershey's Milk Booster Chocolate Syrup | Homemade Lemoneez Syrup | Amul Kool Kesar Flavoured Milk | Amul Lassi | Mother Dairy Sweet Lassi</p>
    </div>
    <div>
        <p class="class">MOBILES: </p>
        <p class="body">iPhone 12 64GB | iPhone 12 Pro 512GB | iPhone 12 128GB | Vivo Y91i | Vivo Y11 | Vivo Y15 | Vivo Y50 | Vivo Y12 Reno2 F | Oppo A12 | Oppo F15 | Oppo A31 | Samsung A71 | Samsung A51 | Samsung A31 | Realme X2 | iPhone 11 | iPhone 11 Pro | iPhone 11 Pro MaxMobile Offers | iphone x | 4G Mobile | Nokia Mobile | Samsung Mobile | iphone | Oppo Mobile | Vivo Mobile</p>
    </div>
         <div> 
            <p class="class">CAMERA: </p>
            <p class="body">GoPro Action Camera | Nikon Camera | Canon Camera | Sony Camera | Canon DSLR | Nikon DSLR
                <p class="class">LAPTOPS: </p>
                   <p class="body"> MacBook Pro M2 | acer Ryzen 3 Dual Core 3250U - (8 GB/256 GB SSD/Windows 11 Home) Z2-493 Thin and Light Laptop | ASUS Vivobook S14 OLED (2022) | ASUS Zenbook 14 OLED (2022) | Realme Book Prime Core i5 11th Gen | Microsoft Surface Go Pentium 128GB | Branded Laptops | Apple Laptops | Acer Laptops | Lenovo Laptops | Dell Laptops | Asus Laptops | HP Laptops | Gaming Laptops | 2 in 1 Laptops | Laptops | Dell latest laptops 2022 | HP latest laptops 2022 | Infinix INBook X1 Neo Series Celeron Quad Core - (8 GB/256 GB SSD/Windows 11 Home) XL22 Thin and Light Laptop | Microsoft Laptops | 12th Gen Intel Core Laptops </p>
                   <p class="class">
                    CLEANING ESSENTIALS: </p>
                    <p class="body">Gainda Phenyl(White) | Colin Glass Cleaner(500ml) | Colin Glass Cleaner(1 l) | Gainda Phenyl(Black) | Colin Glass Cleaner | Cleanzo Black Phenyl | Dettol Liquid Disinfectant(Method Cool) | Dettol Germ Defence Antispectic Liquid | Savlon Surface Disinfectant Spray | Surf Excel Top Load Matic Liquid Detergent | Harpic Disinfectant Liquid Toilet Cleaner | Harpic Disinfectant Liquid Toilet Cleaner(Rose) | Gainda Extreme Power Toilet Cleaner | Harpic Hygienic Toilet Cleaner Block(Lavender) | Harpic Hygienic Toilet Cleaner Block(Citrus) | Feel Fresh Sani Urinal Cubes | Domex Fresh Guard Disinfectant Toilet Cleaner | </p>
                   <p class="class">
                    SNACKS: </p>
                    <p class="body">Haldiram's Classic Salted Chips | Lay's India's Magic Masala Chips | Kurkure Puffcorn Yummy Cheese Puffs | Beyond Snack Kerala Peri Peri Banana Chips | Bingo Street Bites Dahi Chaat Remix Crisps | Kari Kari Chill Garlic Snack | Haldiram's Fatafat Bhel Namkeen | Haldiram's Punjabi Tadka Namkeen | Haldiram's Navratan Mixture Namkeen | Haldiram's Aloo Bhujia | Haldiram's Nimbu Masala Namkeen | Crax Aloo Bhujia | Bikano Aloo Bhujia | Let's Try Garlic Bhujia | Bikano Natkhat Nimbu Namkeen | Bikano Moong Dal Namkeen | Haldiram's Plain Bhujia | </p>
                <p class="class">
                LARGE APPLIANCES: </p>
                <p class="body">TV & Appliances End of Season Sale | Television | Washing Machines | Refrigerators | Air Conditioners | Electric Cookers | Electric Jug(Heater) / Travel Kettles | Induction Cooktops | Inverters / stabilizer | Irons / Iron Box | Mixer Grinder Juicer | Wet Grinders | Chimneys | Microwave Ovens | Vacuum Cleaners | Water Purifier | Fan | MarQ Customer Care</p>
                <p class="class">
                CLOTHING: </p>
                <p class="body">Men Shirts | Kurta Pajama | Kurtas | Men T-Shirts | Jeans | Saree | Dresses | Kids Dresses | Designer Salwar Suits | Bra | Designer Kurtis | Track Pant | Men Kurtas | Gym Wear | Party Dresses | Palazzo Suits | Boys Clothing | Gloves | Nighty | Maxi Dresses | Anarkali | Gowns | Culottes | Salwar Suits | Kurtis | Designer Sarees | Leggings | Shorts | Georgette Sarees | Ethnic Wear | Briefs & Trunks | Nike Watches | Ascot Tie | Corset Tops Tunics | Leather PU Skirts | Corset tops camisoles | Women magenta earrings | No collar jackets | Green dress material | Black patiala kurta set | Men camel shoes casual | Black pathani | Tassel Sarees | Khaki dresses | Kids formal dresses | Mauve shirts | Women henley | uppada pattu sarees | Leopard dresses | Sleeveless shrugs</p>
                <p class="class">FOOTWEAR: </p>
                <p class="body">Shoens | Adidas Shoes | Reebok Shoes | Nike Shoes | Puma Shoes | Boots | Bata Shoes | Woodland Shoes | Skechers Shoes | Sneakers | Womens Boots | Sports Shoes | Loafers | Sandals | Lotto Sports Shoes | Casual Shoes | Womens Skechers Shoes | Asics Sports Shoes | Formal Shoes | School Shoes
                </p>
                <p class="class">GROCERIES: </p>
                <p class="body">PhonePe Grocery Voucher | Hand WashSoap | Cashew Nuts | Sunflower Oil | Eggs | Toilet Cleaner | Harpic | Toilet Cleaner | Dettol Soap | Mustard Oil | Biscuits | Cheese | Patanjali Atta | Fortune Oil | Aashirvaad Atta | Tea</p>
                <p class="class">BEST SELLING ON SHOPIFY: </p>
                <p class="body">Fire-Boltt Ninja Calling Pro Bluetooth Calling Smartwatch 1.69 inch HD Display Smartwatch | Best Gas Geyser | Kitchen Geyser | Nutri Blenders | Portable Air Cooler | Best Air Cooler | Bags | Hitachi Refrigerator 3 Door | Books | Toys | Candles | Helmets | Wall Clocks | Baby Food | Chocolates | Cycles | Calculators | Lipsticks | Mask | Vertiv UPS | Fastrack Watches | Wallets | Earrings | Gold Coins | Realme Pad Mini | Handbags | conekt SW2 Smartwatch | Mivi Duo | Pods a350 | Speaker | Cleaner</p>
                <p class="class">FURNITURE: </p>
                <p class="body">Furniture | Sofas | Beds | Dining sets | Wardrobes | Mattresses | TV Units | Tables | Chairs | Shelves | Bean Bags | Office Chairs | Computer Table | Office Tables | Red Sofa | Wakefit Beds | White Sofa | Wakefit Mattress | Green Sofa | Black Sofa | Brown Sofa</p>
                <p class="class">BGMH: </p>
                <p class="body">Whey Protein | Homeopathy | Bounce Infinity | Christmas Gifts | Calendar 2023 | Online Guitar | Books Store | Musical Instrument Store | Dabur Chyawanprash | Baidyanath Chyawanprash | Energy Drinks | Toys | Milk Drink Mixes | Rakhi | Chyawanprash | Indian Flag | Protein Supplements</p>
        </div></p>
    </div>
</div>
<hr>
<div>
    <div>
        <p class="class">Shopify: The One-stop Shopping Destination</p>
    </div>
    <div>
        <p class="body">E-commerce is revolutionizing the way we all shop in India. Why do you want to hop from one store to another in search of the latest phone when you can find it on the Internet in a single click? Not only mobiles. Shopify houses everything you can possibly imagine, from trending electronics like laptops, tablets, smartphones, and mobile accessories to in-vogue fashion staples like shoes, clothing and lifestyle accessories; from modern furniture like sofa sets, dining tables, and wardrobes to appliances that make your life easy like washing machines, TVs, ACs, mixer grinder juicers and other time-saving kitchen and small appliances; from home furnishings like cushion covers, mattresses and bedsheets to toys and musical instruments, we got them all covered. You name it, and you can stay assured about finding them all here. For those of you with erratic working hours, Shopify is your best bet. Shop in your PJs, at night or in the wee hours of the morning. This e-commerce never shuts down.
        <br>
        <br>
        <br>
        What's more, with our year-round shopping festivals and events, our prices are irresistible. We're sure you'll find yourself picking up more than what you had in mind. If you are wondering why you should shop from Shopify when there are multiple options available to you, well, the below will answer your question.
        </p>
    </div>
    <div>
        <p class="class">Shopify Plus</p>
    </div>
    <div>
        <p class="body">A world of limitless possibilities awaits you - Shopify Plus was kickstarted as a loyalty reward programme for all its regular customers at zero subscription fee. All you need is 500 supercoins to be a part of this service. For every 100 rupees spent on Shopify order, Plus members earns 4 supercoins & non-plus members earn 2 supercoins. Free delivery, early access during sales and shopping festivals, exchange offers and priority customer service are the top benefits to a Shopify Plus member. In short, earn more when you shop more!
        <br>
        <br>
        <br>
        What's more, you can even use the Shopify supercoins for a number of exciting services, like:
        <br>
        An annual Zomato Gold membership
        <br>
        An annual Hotstar Premium membership
        <br>
        6 months Gaana plus subscription
        <br>
        Rupees 550 instant discount on flights on ixigo
        <br>
        Check out https://www.Shopify.com/plus/all-offers for the entire list. Terms and conditions apply.
        </p>
    </div>
    <div>
        <p class="class">No cost EMI</p>
    </div>
    <div>
        <p class="body">In an attempt to make high-end products accessible to all, our No Cost EMI plan enables you to shop with us under EMI, without shelling out any processing fee. Applicable on select mobiles, laptops, large and small appliances, furniture, electronics and watches, you can now shop without burning a hole in your pocket. If you've been eyeing a product for a long time, chances are it may be up for a no cost EMI. Take a look ASAP! Terms and conditions apply.
        </p>
   </div>
   </div>
   <div>
    <p class="class">EMI on Debit cards</p>
   </div>
   <div>
    <p class="body">Did you know debit card holders account for 79.38 crore in the country, while there are only 3.14 crore credit card holders? After enabling EMI on Credit Cards, in another attempt to make online shopping accessible to everyone, Shopify introduces EMI on Debit Cards, empowering you to shop confidently with us without having to worry about pauses in monthly cash flow. At present, we have partnered with Axis Bank, HDFC Bank, State Bank of India and ICICI Bank for this facility. More power to all our shoppers! Terms and conditions apply.
    </p>
   </div>
   <div>
    <p class="class">Mobile Exchange Offers</p>
   </div>
   <div>
    <p class="body">Get an instant discount on the phone that you have been eyeing on. Exchange your old mobile for a new one after the Shopify experts calculate the value of your old phone, provided it is in a working condition without damage to the screen. If a phone is applicable for an exchange offer, you will see the 'Buy with Exchange' option on the product description of the phone. So, be smart, always opt for an exchange wherever possible. Terms and conditions apply.
    </p>
   </div>
   <div>
    <p class="class">Large Appliances</p>
   </div>
   <div>
    <p class="body">Sleek TVs, power-saving refrigerators, rapid-cooling ACs, resourceful washing machines - discover everything you need to run a house under one roof. Our Dependable TV and Appliance Store ensures zero transit damage, with a replacement guarantee if anything goes wrong; delivery and installation as per your convenience and a double warranty (Official Brand Warranty along with an extended Shopify Warranty) - rest assured, value for money is what is promised and delivered. Shop from market leaders in the country like Samsung, LG, Whirlpool, Midea, Mi, Vu, Panasonic, Godrej, Sony, Daikin, and Hitachi among many others.
    </p>
   </div>
   <div>
    <p class="class">Small Home Appliances</p>
   </div>
   <div>
    <p class="body">Find handy and practical home appliances designed to make your life simpler: electric kettles, OTGs, microwave ovens, sandwich makers, hand blenders, coffee makers, and many more other time-saving appliances that are truly crafted for a quicker lifestyle. Live life king size with these appliances at home.
    </p>
   </div>
   <div>
    <p class="class">Lifestyle</p>
   </div>
   <div>
    <p class="body">Shopify, 'India ka Fashion Capital', is your one-stop fashion destination for anything and everything you need to look good. Our exhaustive range of Western and Indian wear, summer and winter clothing, formal and casual footwear, bridal and artificial jewellery, long-lasting make-up, grooming tools and accessories are sure to sweep you off your feet. Shop from crowd favourites like Vero Moda, Forever 21, Only, Arrow, Woodland, Nike, Puma, Revlon, Mac, and Sephora among dozens of other top-of-the-ladder names. From summer staple maxi dresses, no-nonsense cigarette pants, traditional Bandhani kurtis to street-smart biker jackets, you can rely on us for a wardrobe that is up to date. Explore our in-house brands like Metronaut, Anmi, and Denizen, to name a few, for carefully curated designs that are the talk of the town. Get ready to be spoiled for choice.Festivals, office get-togethers, weddings, brunches, or nightwear - Shopify will have your back each time.
    </p>
   </div>
   <div>
    <p class="class">Books,Sports and Games</p>
   </div>
   <div>
    <p class="body">Work hard and no play? We don't believe in that. Get access to best-selling fiction and non-fiction books by your favourite authors, thrilling English and Indian blockbusters, most-wanted gaming consoles, and a tempting range of fitness and sports gadgets and equipment bound to inspire you to get moving.
    </p>
   </div>
   <div>
    <p class="class">Grocery/Supersmart</p>
   </div>
   <div>
    <p class="body6">Launching into the grocery vertical, Shopify introduces Supermart that is out to bring everyday essentials close to you. From pulses, spices, dairy, personal and sanitary care, breakfast essentials, health drinks, spreads, ready to cook, grooming to cleaning agents, we are happy to present everything you need to run a house. Now buy Grocery products for as low as 1 Rupee only - our 1 Rupee Store presents new products every day for a nominal price of 1 Rupee only. Terms and conditions apply.
    </p>
   </div>
</div>
<div class="footer">
    <div>
       <p class="foot">ABOUT
        <br>
        <ul>
            <li>Contact Us</li>
            <li>About Us</li>
            <li>Careers</li>
            <li>Shopify Stories</li>
            <li>Press</li>
            <li>Shopify Wholesale</li>
            <li>Corporate Information</li>
        </ul>
       </p>
    </div>
    <div>
        <p class="foot">HELP
         <br>
         <ul>
             <li>Payments</li>
             <li>Shipping</li>
             <li>Cancellation & Returns</li>
             <li>FAQ</li>
             <li>Report Infringement</li>
         </ul>
        </p>
     </div>
     <div>
        <p class="foot">POLICY
         <br>
         <ul>
             <li>Return Policy</li>
             <li>Terms Of Use</li>
             <li>Security</li>
             <li>Privacy</li>
             <li>Sitemap</li>
             <li>EPR Compliance</li>
         </ul>
        </p>
     </div>
     <div>
        <p class="foot">SOCIAL
         <br>
         <ul>
             <li>Facebook</li>
             <li>Youtube</li>
             <li>Twitter</li>
         </ul>
        </p>
     </div>
     <div>
        <p class="foot" id="cl">Mail Us:
         <br>
         <ul class="b">
             <li id="cl1">Shopify Internet Private Limited,
                <br>
                Faridabad, 121001,
                <br>
                Haryana , India
                <br>
                Telephone: 112-11222121</li>
         </ul>
        </p>
     </div>
     <div>
        <p class="foot">Registered Office Address:
         <br>
         <ul>
             <li>Shopify Internet Private Limited,
                <br>
                Faridabad, 121001,
                <br>
                Haryana , India
                <br>
                Telephone: 112-11222121</li>
         </ul>
        </p>
     </div>
</div>
<div class="end">
    <div class="end1">
        <p class="a">Become a seller</p>
    </div>
    <div class="end1">
         <p class="a">Advertise</p>
    </div>
    <div class="end1">
        <p class="a">Gift Cards</p>
    </div>
    <div class="end1">
        <p class="a">Help Center</p>
    </div>
    <div class="end1">
        <p class="a">© 2007-2022 Shopify.com</p>
    </div>
    
</div>
</body>
<script>
     
</script>
</html>
