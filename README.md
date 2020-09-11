tug of war
<body>
  <h1>Tug-of-war</h1>
  <p>
      Each player taps either the left or right arrow
key to move the red dot toward them. the winner is the
player who has it on their side of the line after 10
seconds.
   </p>
   <canvas width "500" height = "100"></canvas>
  <script src ="script.js"></script>
  var canvas = document.querySelector('canvas')
  var ctx = canvas.getContext('2d')
  
  var middle = 250
  var position = middle 
  function draw () {
  ctx .clearRect(0, 0, 500, 100)
  
</body>
