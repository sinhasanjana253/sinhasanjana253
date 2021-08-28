<html lang="en" dir="ltr">
    <head>
        <meta charset="utf-8">
        <title>MUSIC WEB</title>
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <link rel="stylesheet" href="css/style3.css">
<script src='https://kit.fontawesome.com/a076d05399.js'></script>
        <style>
.middle{
  position: absolute;
  top: 95%;
  transform: translateY(-50%);
  width: 100%;   
  text-align: center;
}
.btn{
  display: inline-block;
  width: 60px;
  height: 60px;
  background: #f1f1f1;
  margin: 10px;
  border-radius: 30%;
  box-shadow: 0 5px 15px -5px #00000070;
  color: #3498db;
  overflow: hidden;
  position: relative;
}
.btn i{
  line-height: 60px;
  font-size: 26px;
  transition: 0.2s linear;
}
.btn:hover i{
  transform: scale(1.3);
  color: #f1f1f1;
}
.btn::before{
  content:"";
  position:absolute;
  width: 220%;
  height: 220%;
  background: #3498db;
  transform: rotate(45deg);
  left: -110%;
  top: 90%;
}
.btn:hover::before{
  animation: aaa 0.7s 1;
  top: -10%;
  left: -10%;
}
@keyframes aaa {
  0%{
    left: -110%;
    top: 90%;
  }50%{
    left: 10%;
    top: -30%;
  }100%{
    top: -10%;
    left: -10%;
  }
}
            .top{
                top: 40%;
                position:absolute;
                height: 45%;
                width: 80%;
                left: 10%;
                border-radius: 7px;
                 box-shadow: 0px 15px 35px orange;
            transition: all ease 0.4s;
                 }
            .new-model{
                position:absolute;
            display: flex;
            border-radius: 7px;
            overflow: hidden;
            box-shadow: 0px 15px 35px #3d2173a1;
            transition: all ease 0.4s;
                top: 17%;
                left: 1%;
                
            }
            .old-model{
                 position:absolute;
            display: flex;
            border-radius: 7px;
            overflow: hidden;
            box-shadow: 0px 15px 35px #3d2173a1;
            transition: all ease 0.4s;
                top: 17%;
                right: 1%;
                
            }
            .verified-model{
                position:absolute;
            display: flex;
            border-radius: 7px;
            overflow: hidden;
            box-shadow: 0px 15px 35px #3d2173a1;
            transition: all ease 0.4s;
                top: 17%;
                right: 17%;
            }
            .notold-model{
                position:absolute;
            display: flex;
            border-radius: 7px;
            overflow: hidden;
            box-shadow: 0px 15px 35px #3d2173a1;
            transition: all ease 0.4s;
                top: 17%;
                left: 17%;
            }
        </style>
           
    </head>
    <body>
    <nav>
        <div class="new">
            <a href="#" class="new-model">
                <img src="https://images.pexels.com/photos/1763075/pexels-photo-1763075.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="" height="150px" width="200px" ></a>
    <a href="#" class="old-model">
                <img src="https://image.shutterstock.com/image-photo/band-practice-home-studio-woman-260nw-1261289038.jpg" alt="" height="150px" width="200px" ></a>  
            <a href="#" class="verified-model">
                <img src="https://cdn.pixabay.com/photo/2016/11/23/15/48/audience-1853662__340.jpg" height="150px" width="200px" ></a>   
            <a href="#" class="notold-model">
                <img src="https://cdn.pixabay.com/photo/2017/11/29/21/35/hangover-2987145__340.jpg" alt="" height="150px" width="200px" ></a>   
        </div>
        <label class="mobile">gaana</label>
        <ul>
        <li><a class="active" href="#">HOME</a></li>
             <li><a href="browse.html">BROWSE</a></li>
             <li><a href="#">RADIO</a></li>
            <li><a href="mymusic.html">MY MUSIC</a></li>
            <li><a href="forms3.html">SIGNUP</a></li>
         </ul>
        <ul>
            <li><a class="solo" href="#">ALBUMS</a></li>
            <li><a class="dolo" href="#">ARTISTS</a></li>
            <li><a class="bitcoin" href="#">SONGS</a></li>
        </ul>
        <iframe class="top"  src="https://open.spotify.com/embed/album/1DFixLWuPkv3KT3TnV35m3" width="300" height="380" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
        <div class="middle">
            <a  class="btn" href="#">
            <i class="fab fa-facebook-f"></i></a>
            <a class="btn" href="#">
            <i class="fab fa-twitter"></i></a>
        
            <a class="btn" href="#">
            <i class="fab fa-google"></i></a>
        
            <a class="btn" href="#">
            <i class="fab fa-instagram"></i></a>
        
            <a class="btn" href="#">
            <i class="fab fa-youtube"></i></a>
         </div>
         </nav>
   </body>
</html>
© 2021 Git
