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

Q= 3

<!DOCTYPE>
 <HTML>

   <head>

            <title>  3 question </title>

   </head>
    <link rel="stylesheet" href=" 7 assignment 3.css">

    <body>

      
        <div class="main"> 

          
            <div class="image">

             
           </div>

           <div class="text"> 
          
                 <h3> The Earth</h3>

               <p> The "Earth theory" can refer to a few different concepts: (1) Geological Theory (James Hutton's
                   "Theory of the Earth"), (2) theories about Earth's formation, or (3) the Flat Earth theory. Hutton's
                   work laid the foundation for modern geology by proposing that natural forces acting over long periods 
                   shaped the Earth. Theories about Earth's formation, like the core accretion model, explain how our planet      
                   coalesced from a solar nebula. Finally, the Flat Earth theory is a pseudoscientific belief that Earth is not 
                   a sphere, but a flat plane, which is contradicted by scientific evidence.The "Earth theory" can refer to a few different concepts: (1) Geological Theory (James Hutton's
                   "Theory of the Earth"), (2) theories about Earth's formation, or (3) the Flat Earth theory. Hutton's
                   work laid the foundation for modern geology by proposing that natural forces acting over long periods 
                   shaped the Earth. Theories about Earth's formation, like the core accretion model, explain how our planet      
                   coalesced from a solar nebula. Finally, the Flat Earth theory is a pseudoscientific belief that Earth is not 
                   a sphere, but a flat plane, which is contradicted by scientific evidence.The "Earth theory" can refer to a few different concepts: (1) Geological Theory (James Hutton's
                   "Theory of the Earth"), (2) theories about Earth's formation, or (3) the Flat Earth theory. Hutton's
                   work laid the foundation for modern geology by proposing that natural forces acting over long periods 
                   shaped the Earth. Theories about Earth's formation, like the core accretion model, explain how our planet      
                   coalesced from a solar nebula. Finally, the Flat Earth theory is a pseudoscientific belief that Earth is not 
                   a sphere, but a flat plane, which is contradicted by scientific evidence.  </p>

           </div>





       </div>  
   </body>
 </HTML>

 style=
 .main{  

  border: solid 2px black;
  height: 400px;
   

.image{

   border: solid 2px black;
   height: 380px;
   width: 500px;
   background-image: url("https://thumbs.dreamstime.com/b/earth-moon-view-space-night-europe-46110305.jpg");
   background-size: cover;
   float: right;
   margin-top: 10px;
   margin-right:10px;
}


q-4 


<!DOCTYPE>

  <HTML>
   
    <head>

      <title>  4 question    </title>

    </head>

    <link rel="stylesheet" href="7 assignment 4.css">

    <body>

           
             
          <div class="navbar">
     
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Services</a>
            <a href="#">Contact</a>

            </div>

          
  
             <div class="body-part">

               <div class="section">Section 1</div>
               <div class="section">Section 2</div>
               <div class="section">Section 3</div>
               <div class="section">Section 4</div>
         
               </div>











          </div>
      

               </body>
             </HTML>

style=



* {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

header{

  position: sticky;

}



.navbar{
   
    position: fixed;
    background-color: black;
    height: 80px;
    width: 100%;
    display: flex;
    justify-content: space-evenly;
    padding: 20px;
    

   
}

.navbar a{

   color: white;
   font-size: 18px;
 }
     

.body-part{

       padding: 20px;

}
.section{

height: 200px;
border: solid 2px black;


}

q=5 

   <!DOCTYPE html>

<head>
  
  <title>Z-Index Example</title>
  
  <link rel="stylesheet" href="7 assignment 5.css"> 
 
</head>
<body>

  <div class="box box1">Box 1</div>
  <div class="box box2">Box 2</div>
  <div class="box box3">Box 3</div>

</body>
</html>

style=

   .box {
      width: 150px;
      height: 150px;
      position: absolute;
    }

    .box1 {
      background-color: red;
      top: 40px;
      left: 40px;
      z-index: 1;
    }

    .box2 {
      background-color: blue;
      top: 80px;
      left: 80px;
      z-index: 2;
    }

    .box3 {
      background-color: green;
      top: 120px;
      left: 120px;
      z-index: 0;





             






   
