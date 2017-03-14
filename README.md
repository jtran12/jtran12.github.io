# Soundboard

* D
  * <button onclick="myFunction('d-naisu')">Naisu</button>
  * <button onclick="myFunction('d-what-a-frag-hunter')">What a frag hunter</button> 
  
* G
  * <button onclick="myFunction('g-nice')">nice</button>
  * <button onclick="myFunction('g-wat')">wat</button>
  
* J
  * <button onclick="myFunction('j-game-sucks')">Game sucks</button>

* P
  * <button onclick="myFunction('p-what')">Game sucks</button>

* Ro
  * <button onclick="myFunction('r-why-behind')">What why</button>

* T
  * <button onclick="myFunction('tran-WAT')">WAT</button>

# Notes



<script>

 function myFunction(name) {
  var audiofile = '/sounds/' + name + '.wav';
  var audio = new Audio(audiofile);
  audio.play();
 }
 
 
 
</script>
