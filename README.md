# Soundboard

* D
  * <button onclick="myFunction('naisu')">Naisu</button>
  
* G
  * 

<script>
 function myFunction(name) {
  if (name === 'naisu'){
   var audio = new Audio('/sounds/d-naisu.wav');
  }
  
  audio.play();
 }
</script>
