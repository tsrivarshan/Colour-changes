# Colour-changes
<!doctype html>
<html>
 <head> 
  <script>
  function myfun1(){
   document.getElementById("G").style.background="red";
 
  }
  function myfun2(){
   document.getElementById("G").style.background="yellow";
  }
  function myfun3(){
   document.getElementById("G").style.background="violet";
  }
 </script> 
 </head> 
 <body> 
  <table border="2" align="center" width="50"> 
   <tbody> 
    <tr> 
     <th id="G" style="font-size:40px" align="center" colspan="3"> HELLO! &#128591 JAVASCRIPT </th> 
    </tr> 
    <tr> 
     <td text align="center"><button type="button" onclick="myfun1();">Mr.Red&#128545</button></td> 
     <td text align="center"><button type="button" onclick="myfun2();"> Mr.Yellow&#128512</button></td> 
     <td text align="center"><button type="button" onclick="myfun3();"> Mr.Violet&#128127</button></td> 
    </tr> 
   </tbody> 
  </table> 
 </body>
</html>
