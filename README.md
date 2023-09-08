# Jquery
Write a program to find show and hide functions in JQuery.
<!DOCTYPE html>    
<html>    
<head>    
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>    
<script>    
$(document).ready(function(){    
    $("button").click(function(){    
        $("div.d1").toggle();    
    });    
});    
</script>    
</head>
<body>    
<button>Toggle</button>    
<div class="d1" style="border:1px solid black;padding:10px;width:250px">    
<p><b>This is a little poem: </b><br/>      
Twinkle, twinkle, little star<br/>      
How I wonder what you are<br/>      
Up above the world so high<br/>      
Like a diamond in the sky<br/>      
Twinkle, twinkle little star<br/>      
How I wonder what you are</p>     
</div>    
</body>    
</html>

Write a program to wrap all the text using JQuery.
<!DOCTYPE html>  
<html>  
<head>  
<title>The jQuery Example</title>  
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>  
<script type="text/javascript" language="javascript">  
         $(document).ready(function() {  
            $("div").click(function () {  
               var content = '<div class="div"></div>';  
               $("#destination").wrap( content );  
            });  
         });  
</script>  
<style>  
.div{ margin:5px;padding:2px; border:2px solid #666; width:60px;}</style>  
</head>  
<body>  
<p>Click on any square to wrap the text:</p>  
<div class="div" id="destination">We are going to wrap this text</div>  
<div class="div" style="background-color:orange;">ONE</div>  
<div class="div" style="background-color:yellow;">TWO</div>  
<div class="div" style="background-color:green;">THREE</div>  
</body>  
</html>

Write a program to to get the background-color of first matched element using JQuery.
<!DOCTYPE html>  
<html>  
<head>  
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>  
<script>  
$(document).ready(function(){  
    $("button").click(function(){  
        alert("Background color = " + $("p").css("background-color"));  
    });  
});  
</script>  
</head>  
<body>  
<h2>This is a heading</h2>  
<p style="background-color:#ff0000">The background-color of this paragraph is red.</p>  
<p style="background-color:#00ff00">The background-color of this paragraph is green.</p>  
<p style="background-color:#0000ff">The background-color of this paragraph is blue.</p>  
<button>Click here to get the background-color of first matched element</button>  
</body>  
</html> 

Write a program to set multiple styles for all selected elements.
<!DOCTYPE html>  
<html>  
<head>  
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>  
<script>  
$(document).ready(function(){  
    $("button").click(function(){  
        $("p").css({"background-color": "blue", "font-size": "200%"});  
    });  
});  
</script>  
</head>  
<body>  
<h2>This is a heading</h2>  
<p style="background-color:#ff0000">The background-color of this paragraph is red.</p>  
<p style="background-color:#00ff00">The background-color of this paragraph is green.</p>  
<p style="background-color:#0000ff">The background-color of this paragraph is blue.</p>  
<p>This paragraph has no background-color.</p>  
<button>Click here to set multiple styles for all selected elements.</button>  
</body>  
</html>
