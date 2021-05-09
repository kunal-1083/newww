<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Our Website</title>
    <link rel="stylesheet" href="css/style.css">
    <style>
        *{
    margin: 0px;
    padding: opx;
}
#navbar{
    display: flex;
    align-items: center;
    position:relative;

}
#logo img{
    margin: 8px 15px;
    width: 95px;
    height:41px
}
#navbar ul{
    display: flex;
    padding: 10px;
}
#navbar ul li{
    list-style: none;
    font-size: 15px;
    padding: 5px;
}
#navbar ul li a{
    color: aliceblue;
    display: block;
    padding: 3px 15px;
    text-decoration: none;
}
#navbar ul li a:hover{
    color:black;
    background-color:white;
    
    
}
#navbar::before{
    content: "";
    background-color: black;
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: -1;
    opacity: 0.5;
}
#screen{
    display: flex;
    flex-direction: column;
    padding: -3px 200px;
    justify-content: center;
    text-align: center;
    opacity: 1;
    height: 100px;
    font-size: 10px;
}
#screen::before{
    content: "";
    position:absolute;
    background:url('../b6new.jpg') no-repeat center center/cover;
    width: 100%;
    height: 100%;
    z-index: -1;
    /* opacity: 0.9; */
}
.primary{
    font-size: 2.8rem;
    padding: 12px;
}
.primary1{
    font-size: 2.8rem;
    padding: 12px;
    text-align: center;
    margin-top: 230px;
}
.secondary{
    font-size: 1.5rem;
    padding: 12px;
    text-align: center;

}
#content{
    text-align: center;
}
#screen h2{
    color: lightgoldenrodyellow;
    /* text-align: right; */
    margin-left:-436px;
    margin-top: 150px;
    font-family:inherit;
}
    
    
#screen p{
    width: 809px;
    font-size: 15px;
    /* margin-left: 578px; */
    margin-top: 1px;
    padding: 2px;
    color: white;
    font-family: inherit;
}
.btn{
    width: 100px;
    margin-left: 350px;   
    padding: 5px;
    margin-top: 30px;
    margin-top: 10px;    
    border-radius: 5px;
    border: 2px solid black;
    text-decoration: underline;
    cursor: pointer;
}
#services{
    margin: 0px;
    display: flex;
}
.services-box{
    background-color:lightgray;
}
#services .box{
    border: 2px solid black;
    padding: 34px;
    margin: 7px 13px;
    border-radius: 23px;
    background-color: white;
    
}
#services .box img{
    height: 100px;
    display: block;
    margin: auto;
    width: 100px;
}
.center{
    text-align: center;
}
#client{
    display: flex;
    justify-content: center;
    text-align: center;
}
#client img{
    height: 50px;
    padding: 10px;
    margin: 10px;
}
#client-section::before{
    /* border: 2px solid red; */
    content: "";
    position: absolute;
    background: url(simple1.png) no-repeat center center/cover;
    width: 100%;
    height: 28%;
    z-index: -1;
    opacity: 0.4;
}
.primary2{
    color: black;
    font-size: 2.8rem;
}
#contact::before{
    content: "";
    position: absolute;
    background: url(contact.jpg) no-repeat center center/cover;
    width: 100%;
    height:80%;
    z-index: -1;
    opacity: 0.7;

}
.primary3{
    font-size: 2.5rem;
    padding: 2px;
  
}
footer{
    color: white;
    background-color: black;

}
#contact-box input,
#contact-box textarea{
    width: 100%;
    padding: 0.5rem;
    border-radius: 6px;
    
}
#contact-box{
    display: flex;
    text-align: center;
    justify-content: center;
    
}
#contact-box label{
    font-size: 16px;

}

    </style>
</head>
<body>
   <nav id="navbar">
        <div id="logo">
            <img src="logo3.jpg" alt="">
        </div>
        
        <ul>
           <li class="item"><a href="#">Home</a></li>
           <li class="item"><a href="#">About us</a></li>
           <li class="item"><a href="#">Services</a></li>
           <li class="item"><a href="#">contact us</a></li>
        </ul>
           
   </nav>
   <section id="screen">
       <h2 class="primary"> Welcome To Our Food Tour...</h2>
       <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita facilis rerum,<br> dolorem atque consequuntur ad non quidem nam iure soluta.</p>
       <!-- <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.</p> -->

       <button class="btn"> Order Now</button>
   </section>
   <section class="services-box">
     <h1 class="primary1"> Our services..</h1>
     <div id="services">
         <div class="box">
             <img src="imgweb/hhhh.jpg" alt="">
             <h2 class="secondary">Food Ordering</h2>
             <p id="content">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Suscipit sed tempora rem quaerat officiis quod. Praesentium officia numquam soluta vero?</p>

         </div>
         <div class="box">
             <img src="imgweb/hello.jpg" alt="">
             <h2 class="secondary">Food catering</h2>
             <p id="content">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Suscipit sed tempora rem quaerat officiis quod. Praesentium officia numquam soluta vero?</p>

         </div>
         <div class="box">
             <img src="imgweb/images.jpg" alt="">
             <h2 class="secondary">Food Delivering</h2>
             <p id="content">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Suscipit sed tempora rem quaerat officiis quod. Praesentium officia numquam soluta vero?</p>

         </div>


     </div>


   </section>
   <section id="client-section">
        <h1 class="primary2 center"> Our Clients..</h1>
        <div id="client">
            <div class="class-item center">
                <img src="imgweb/fvvv.jpg" alt="">
            </div>
        
            <div class="class-item center">
                <img src="imgweb/vvvv.jpg" alt="">
            </div>
      
            <div class="class-item center">
                <img src="imgweb/qqqq.jpg" alt="">
            </div>
      
            <div class="class-item center">
                <img src="imgweb/tgtgtg.png" alt="">
            </div>
        </div>
    </section>

    <section id="contact">
        <h1 class="primary3 center">contact us here.. </h1>
        <div id="contact-box">
            <form action="">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" name="name" id="name" placeholder="enter your name">
                </div>
                <div class="form-group">
                    <label for="name">Email:</label>
                    <input type="email" name="email" id="name" placeholder="enter your email">
                </div>
                <div class="form-group">
                    <label for="phone">Phone no.:</label>
                    <input type="phone" name="phone" id="phone" placeholder="enter your phone no.">
                </div>
                <div class="form-group">
                    <label for="message">message:</label>
                    <textarea name="message" id="message" cols="30" rows="10" placeholder="enter a message"></textarea>
                </div>
            </form>
        </div>

    </section>
    <footer>
        <div class="center">
            copyright &copy; www.onlinefoodtour.com.
        </div>
    </footer>
             
        

</body>
</html>
