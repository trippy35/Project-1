<html>
   <head>
      <title>The Machine Never Stops</title>
      <script type = "text/javascript" 
         src = "https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js">
      </script>
		
      <script type = "text/javascript" 
         src = "https://ajax.googleapis.com/ajax/libs/jqueryui/1.11.3/jquery-ui.min.js">
      </script>
    
<!-- I used a javascript pluggin to add the explosion effect -->

      <script type = "text/javascript" language = "javascript">
   
         $(document).ready(function() {

            $("#hide").click(function(){
               $(".target").hide( "explode", {pieces: 16 }, 2000 );
            });

            $("#show").click(function(){
               $(".target").show( "explode", {pieces: 16}, 2000 );
            });
				
         });
			
      </script>
		
      <style>
        img {
          width: 100%
        }
         p {background-color:#bca; width:200px; border:1px solid green;}
         div{width:300px; height:100px; background: blue;}
      </style>
      
   </head>
	
   <body>
     
      <p>Imagine the world was this blue box. It's a perfectly nice size blue box and there is nothing wrong with it. 
        However, with the advancement of AI there is a possibility that
        we could be taken over by machines. The world seems at peace now but I strongly believe
        technology and man made machines will lead to our demise.  

      </p>
    
      <p>Click on any of the buttons below </p>
      
      <button id = "hide"> Machines </button>
      <button id = "show"> The world </button> 
  
      <div class = "target">
      </div>
      <div>
        <img src="terminator_endoskeleton_1020.0.jpg">
        
          </div>
   </body>
</html>


