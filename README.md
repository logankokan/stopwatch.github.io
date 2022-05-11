

<!doctype html>    
   <html>    
      <head>    
         <title>Stopwatch</title>    
         <link rel="stylesheet" href="secundomer.css"/>    
      </head>    
      <body>    
    
         <div class="MainContainer">    
            <input id="start" name="controls" type="radio" />    
            <input id="stop" name="controls" type="radio" />    
            <input id="reset" name="controls" type="radio" />    
         <div class="stopwatch">    
            <div class="box">    
               <div class="number tensPlaceHours moveuptens">0 1 2 3 4 5 6 7 8 9</div>    
            </div>    
            <div class="box">    
               <div class="number onesPlaceHours moveuptens">0 1 2 3 4 5 6 7 8 9</div>    
            </div>    
    
            <div class="box divider">    
               <div class="number">:</div>    
            </div>    
    
            <div class="box">    
               <div class="number tensPlaceMinutes moveupsix">0 1 2 3 4 5 6</div>    
            </div>    
            <div class="box">    
               <div class="number onesPlaceMinutes moveuptens">0 1 2 3 4 5 6 7 8 9</div>    
            </div>    
    
            <div class="box divider">    
               <div class="number">:</div>    
            </div>    
    
            <div class="box">    
               <div class="number tensPlaceSeconds moveupsix">0 1 2 3 4 5 6</div>    
            </div>    
            <div class="box">    
               <div class="number onesPlaceSeconds moveuptens">0 1 2 3 4 5 6 7 8 9</div>    
            </div>    
    
            <div class="box divider">    
               <div class="number">:</div>    
            </div>     
   
    
            <div class="box">    
               <div class="number onesPlaceMiliSeconds moveuptens">0 1 2 3 4 5 6 7 8 9</div>    
            </div>    
            <div class="box">    
               <div class="number tensPlaceMiliSeconds moveuptens">0 1 2 3 4 5 6 7 8 9</div>    
            </div>    
            <div class="box">    
               <div class="number hundredsPlaceMiliSeconds moveuptens">0 1 2 3 4 5 6 7 8 9</div>    
            </div>    
      </div>    
      <!--labels for controls-->    
       <div id="stopwatch_controls">    
           <label for="start">START</label>    
           <label for="stop">STOP</label>    
           <label for="reset">RESET</label>    
       </div>    
      </div>    
   </body>    
</html>  
