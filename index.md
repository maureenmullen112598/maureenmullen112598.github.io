<!DOCTYPE html>
<html>
    <head>
        <script type="text/javascript" src="processing.js"></script>
        <meta charset="utf-8">
        <title>New webpage</title>
        <style>
            body{
            background-color: rgb(201,227,255);
           }
           hr{
               margin-top: 200px;
               margin-left:130px;
               width:1668px;
               height:0;
               background-color:rgb(242, 19, 242);
               border:solid;
               border-width:0.5px;
           }
           .hello-text{

            font-size:100px;
            font-family: helvetica;
            font-weight: lighter;
            position: absolute;
            margin-left:20px;
            background-color: white;
            border: solid 1px;
            padding: 5px;



           }
           #picme{
            margin-top: 10px;
            float: left;
            width: 500px;
            position:absolute;
            top:10px;
            left:150px;
        }
           img{
            border-radius: 50%;
  -webkit-transition: -webkit-transform .2s;
          transition:         transform .2s;
           }
           img:hover {
 -webkit-transform: rotate(7deg);
          transform: rotate(7deg);
           }
        .text-02{
position:absolute;
left:300px;
top:400px;
border:solid 1px;
background-color: white;
padding:5px;
font-size: 50px;
font-family: helvetica;
font-weight: lighter;
        }


        </style>
    </head>
    <body>
        <canvas data-processing-sources="COMP_cutie_02.pde"></canvas>
     
    <p class="hello-text">hello</p>
    
    <img id="picme" src="https://drive.google.com/file/d/1hcdw6UxusDdG0-vyQHNf5bZWM17oLlCm/view?usp=sharing">

    <p class="text-02">its nice to see u</p>
  

        
    </script>
</body>
   


    </body>
</html>
