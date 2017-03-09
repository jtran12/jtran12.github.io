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
  Initial<input type="number" name="initial"><br>
  <button onclick="calculate(total, initial)">Submit</button>
</form>

<script>

 function myFunction(name) {
  var audiofile = '/sounds/' + name + '.wav';
  var audio = new Audio(audiofile);
  audio.play();
 }
 
 function calculate(total, initial) {
  var count = 0;
  while ((total - initial) >= initial){
   count = count + 1;
   total = total - initial;
   initial = initial*2
  }
  alert(count);
  
 }
 
 
</script>
