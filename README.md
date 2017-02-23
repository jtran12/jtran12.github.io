# Soundboard

* D
  * <button onclick="myFunction('naisu')">Naisu</button>
  * <button onclick="myFunction('fraghunt')">What a frag hunter</button> 
  
* G
  * <button onclick="myFunction('g-nice')">nice</button>
  * <button onclick="myFunction('g-wat')">wat</button>

* R
  * <button onclick="myFunction('r-why-behind')">What why</button>

* T
  * <button onclick="myFunction('tran-wat')">WAT</button>

<script>
 function myFunction(name) {
  if (name === 'naisu'){
   var audio = new Audio('/sounds/d-naisu.wav');
  }
  else if (name === 'fraghunt'){
   var audio = new Audio('/sounds/d-what-a-frag-hunter.wav');
  }
  else if (name === 'g-nice'){
   var audio = new Audio('/sounds/g-nice.wav');
  }
  else if (name === 'g-wat'){
   var audio = new Audio('/sounds/g-wat.wav');
  }
  else if (name === 'r-why-behind'){
   var audio = new Audio('/sounds/r-why-behind.wav');
  }
  else if (name === 'tran-wat'){
   var audio = new Audio('/sounds/tran-WAT.wav');
  }
  
  audio.play();
 }
</script>
