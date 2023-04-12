# project1bysuccess
#hi this is my first project by success that reproduced a shoe store on jumia

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sneaker</title>
    <style>
        *{
            margin: 0;
            user-select: none;
        }
      body{
        background-color: blanchedalmond;
      }
      #sneakers{
        font-weight: bolder;
        font-size: 30px;
        margin-top: 30px;
        margin-left: 15px;
      }                
      h5{
        float: left;
        margin-top: -17px;
       
        
      }
      #collection{
        display: flex;
       margin-left: 150px;
     
      }
      #men{
        display: flex;
       margin-left: 250px;
     
      }
      #women{
        display: flex;
       margin-left: 350px;
     
      }
      #about{
        display: flex;
       margin-left: 450px;
     cursor: pointer;
      }
      #contact{
        display: flex;
       margin-left: 550px;
     
      }
      #younglady{
       height: 40px;
       width: 40px;
       border-radius: 50%;
       display: flex;
      margin-left: 930px;
      margin-top: -35px;
      }    
      #shoesdisplay{
        margin-left: 80px;
        border-radius: 29px;
        box-shadow: 10px 10px 10px rgb(170, 164, 164),-10px -10px 10px rgb(243, 237, 237);
        width: 290px;
        height:350px;
          margin-top: 30px;
          filter:saturate(160%);
      }            
      #img1{
        height: 90px;
        width: 62.5px;
        float: left;
        padding-left: 10px;
        border-radius: 20px;
      }
      #img2{
        height: 90px;
        width: 62.5px;
        float: left;
        padding-left: 10px;
        border-radius: 20px;
      }
      #img3{
        height: 90px;
        width: 62.5px;
        float: left;
        padding-left: 10px;
        border-radius: 20px;
      }  
      #img4{
        height: 90px;
        width: 62.5px;
        float: left;
        padding-left: 10px;
        border-radius: 20px;
      }
      #familyshoe{
        margin-left: 80px;
        margin-top: 17px;
      }
      #minor{
        margin-left: 550px;
        display:block;
        width: 300px;
        margin-top: -350px;
        
      }   
      h6{
        margin-bottom: 20px;
        font-size: 14px;
        color:rgb(236, 130, 37);
      }     
      #fall{
        font-size: 35px;
        margin-bottom: 20px;
      }
      #firstcol{
        margin-bottom: 0.00px;
      }
      
  #price{
    margin-top: 30px;
    font-size: 30px;
    font-weight: bolder;
  }
  #per{
    font-weight: bolder;
    margin-left: 150px;
    margin-top: -22px;
    background-color: pink;
    width: 40px;
    height: 25px;
    line-height: 30px;
  }
  #no{
    text-transform: capitalize;
    text-decoration: line-through;
    opacity: 1;
  }
  #mainadd{
    height: 50px;
    background-color: rgb(169, 170, 170);
    width: 130px;
    border-radius: 14px;
  }
  #substrate{
    background-color: transparent;
    width: 30px;
    height: 50px;
    border-radius: 14px;
    font-size: 40px;
    text-align: center;
    border-right: 2px solid black;
    cursor: pointer;
     
  }         
  #substrate:active{
background-image: linear-gradient(110deg,yellow,pink,red);
  }

  #add:active{
background-image: linear-gradient(110deg,orange,pink,aqua);
  }
  #add{
    background-color: transparent;
    width: 30px;
    height: 50px;
    border-radius: 14px;
    font-size: 40px;
    text-align: center;
    margin-top: -50px;    
    margin-left:100px;
    border-left: 2px solid black;   
    cursor: pointer;
  }
  #view{
    background-color: transparent;
    height: 50px;
    width: 70px;
    margin-left: 30px;
    font-size: 40px;
    text-align: center;
    margin-top: -50px; 
  }
  #cart{
    height: 60px;
    width: 120px;
    background-color: orangered;
    font-size: 20px;
    color: white;
    margin-left: 160px;
    margin-top: -290px;
  }

  #shoe_1{
    cursor: pointer;
  }

  #shoe_2{
    cursor: pointer;
  }

  #shoe_3{
    cursor: pointer;
  }

  #shoe_4{
    cursor: pointer;
  }
    </style>             
</head>         
 
<body> 
    <h2 id="sneakers">sneakers</h2>    
    <h5           id="collection">collection</h5> 
    <h5 id="men">men</h5>
    <h5 id="women">women</h5>
    <h5 id="about">About</h5>
    <h5 id="contact">contact</h5>     
    <img src="Screenshot_20221213-205737.png" alt="image of a young lady" id="younglady">

<!-- space -->
<div class="leftmain"> 
    <img src="images (1).jpg" alt="shoes displays" id="shoesdisplay">
    <!-- shoe clicking icon -->
    <div id="familyshoe">
<!-- first one -->
       <div id="shoe_1"><img src="images (1).jpg" alt="sneakershow1" id="img1" onclick="img1()"> </div>
<!-- second one -->
       <div id="shoe_2"  onclick="img2()"><img src="images (2).jpg" alt="sneakershow2" id="img2"></div>
<!-- third one -->
       <div id="shoe_3"><img src="images (3).jpg" alt="sneakershow3" id="img3"></div>
       <!-- last one -->
       <div id="shoe_4">  <img src="photo-1595950653106-6c9ebd614d3a.jpg" alt="sneakershow4" id="img4"> </div>
    </div>                    

     <div id="minor">
      <h6>sneakers company</h6>
      <h2 id="fall"><nobr>fall limited Edition <br>Sneakers</h2>
        <p id="firstcol">
      these low profile sneakers are your perfect causal wear</p> </nobr> <br> <nobr> 
        <p id="middle">
      companion. Featuring a durable rubber outer sole, they'll</p></nobr> <br>  
      withstand everything the weather can offer.
      <br>
      <div id="price">$125.00</div>  
      <div id="per">50%</div>
      <div id="no">$250.00</div>
      <div id="mainadd">
 <div id="substrate" >-</div>
 <div id="add" onclick="add()">+</div>
 <div id="view">0</div>
      </div>   
      <button type="submit" id="cart">Add to cart</button>
      </div>
      
      </div>
                      
  </div>
  <script>
    let view = document.getElementById("view");

let add = document.getElementById("add")

let substrate = document.getElementById("substrate")

let shoesdisplay = document.getElementById("shoesdisplay")

let shoe_1 = document.getElementById("shoe_1")

let shoe_2 = document.getElementById("shoe_2")

let shoe_3 = document.getElementById("shoe_3")

let shoe_4 = document.getElementById("shoe_4")

    let num = 0;
    // the add function
    // function add(){
    //   num++        
    //   view.innerText = num
    // }          
    // the substare function
    // function substrate(){
    //   num--     
    //   view.innerText = num;
    // }                                
    add.addEventListener("click",()=>{
    num++
      view.innerText = num
    })
    // }                                
    substrate.addEventListener("click",()=>{
    num--
      view.innerText = num
    })

    shoe_1.addEventListener("click",()=>{
      shoesdisplay.setAttribute("src","images (1).jpg")
    })

    shoe_2.addEventListener("click",()=>{
      shoesdisplay.setAttribute("src","images (2).jpg")
    })      
    
    shoe_3.addEventListener("click",()=>{
      shoesdisplay.setAttribute("src","images (3).jpg")
    })
    
    shoe_4.addEventListener("click",()=>{
      shoesdisplay.setAttribute("src","photo-1595950653106-6c9ebd614d3a.jpg")
    })      
  </script>   
</body> 
</html>      
