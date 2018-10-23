# Song-of-the-Day
Give the user their song of the day based on their choices from a vast list of category lineages.


<body>
  <p id="mainlist">
    <span id="rock" onclick="rock()">rock </span><span id="reggae">reggae </span><span id="jazz">jazz </span>
  </p>
  <p id="result">
    
  </p>
  
  <script>
  
    function rock() {
      document.getElementById("mainlist").style.display = "none";
      document.getElementById("result").innerHTML = "classic rock hard rock"
    }
  </script>
</body>
