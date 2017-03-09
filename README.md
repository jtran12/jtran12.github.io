# Soundboard

* D
  * <button onclick="myFunction('d-naisu')">Naisu</button>
  * <button onclick="myFunction('d-what-a-frag-hunter')">What a frag hunter</button> 
  
* G
  * <button onclick="myFunction('g-nice')">nice</button>
  * <button onclick="myFunction('g-wat')">wat</button>
  
* J
  * <button onclick="myFunction('j-game-sucks')">Game sucks</button>

* Ro
  * <button onclick="myFunction('r-why-behind')">What why</button>

* T
  * <button onclick="myFunction('tran-WAT')">WAT</button>

# Calculator

<form>
  Bankroll <input type="number" name="total"><br>
  Initial <input type="number" name="initial"><br>
  <input type="submit" value="Submit">
</form>

<script>
 function myFunction(name) {
  var audiofile = '/sounds/' + name + '.wav';
  var audio = new Audio(audiofile);
  audio.play();
 }
</script>
