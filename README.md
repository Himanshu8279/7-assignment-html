# 7-assignment-html

q-1
<!DOCTYPE>

  <html>
    <head>

      <title> question 1  </title>
       <link rel="stylesheet" href = " 7 assignment 1.css ">

   </head>


  <body>

           <div class="main">
           <div id="A" class="box">A</div>
           <div id="B" class="box">B</div>
           <div id="C" class="box">C</div>
           <div id="D" class="box">D</div>
           <div id="E" class="box">E</div>

           </div>
     


 


    </body>
   </html>

style=

*{

   box-sizing: border-box;
}
body{

    padding: 0;
    margin: 0;
}

.box {
  display: inline-block;
  width: 100px;
  height: 100px;
  background: red;
  color: white;
}
.main{

    border: solid  2px black; 
    height: 225px;
    width: 225px;
    margin-top: 100px;
    margin-left: 180px;
    position: absolute;

       }

#A{
  
   position: absolute;
   top: 60px;
   left: 60px;
   text-align: center;

}

#D{

    position: absolute;
    top:120px;
    left: 0px;
    text-align: center;

}

#E{   position: absolute;
    top:120px;
    right: 0px;
    text-align: center;


}

#C{

    position: absolute;
    top:0x;
    right: 0px;
    text-align: center;



}


#B{
   
text-align: center;


}

Q=3

<!DOCTYPE>
   <HTML>
     
       <HEAD>

         <TITLE> 2 QUESTION     </TITLE>

      </HEAD>

     <link rel="stylesheet" href=" 7 assignment 2.css ">

   <BODY>

      <h1>  absolute position</h1>


           <div class="main">
       
                  <div class=" box box1 "> box1 </div>
   


                  <div class=" box box2 "> box2 </div>
          </div>
  

   <h1>  relative position </h1>

     <div class= "main2">
  
          <div class=" box box3"> box3 </div>

          <div class="box box4"> box4 </div>
          <div class="box box5"> box5 </div>

    
     </div>



     </BODY>
  </HTML>

STYLE= 

.main{

  border: solid 2px black;
  display: flex;
  height: 400px;
  width: 600px;


}




.box{

     border: solid 2px black;
     height: 200px;
     width : 200px;
     background-color: green;
     
}

.box2{

  position: absolute;
  top: 100px;
  left: 40px;


}


.main2{

  border: solid 2px black;
  display: flex;
  height: 400px;
  width: 700px;

}

.box4{

  position: relative;
  top: 20px;
  left: 40px;
}










   
