# Soundboard

* D
  * <button onclick="myFunction('d-naisu')">Naisu</button>
  * <button onclick="myFunction('d-what-a-frag-hunter')">What a frag hunter</button> 
  
* G
  * <button onclick="myFunction('g-nice')">nice</button>
  * <button onclick="myFunction('g-wat')">wat</button>

* R
  * <button onclick="myFunction('r-why-behind')">What why</button>

* T
  * <button onclick="myFunction('tran-wat')">WAT</button>

<script>
 function myFunction(name) {
  var audiofile = '/sounds/' + name + '.wav';
  var audio = new Audio(audiofile);
  audio.play();
 }
</script>
