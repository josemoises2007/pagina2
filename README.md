# pagina2
jose
<h1>este codigo é pra fazer um progress</h1>
<pre><code>



<progress id="myprogress" value="10" max="100" ></progress><center>

<script>
  setInterval( function(){
      let value = document.getElementById("myprogress").value;
      value = Math.min(value + .10, 200) % 100;
      document.getElementById("myprogress").value = value;
      document.getElementById("progress-text").innerText = Math.round(value);
  }, 1 );
  </script>
  #myprogress{
    width: 650px;
  height: 30px;
  
}
progress:not([value]) {
   /* Styling here */
}
progress[value] {
  width: 650px;
  height: 970px;
}
progress[value] {
  /* Reset the default appearance */
  -webkit-appearance: none;
   appearance: none;

  width: 250px;
  height: 20px;
}

/* el dentro */
progress[value]::-webkit-progress-bar {
 
  background-color: #eee;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.25) inset;
}
/* el fuera */
progress[value]::-webkit-progress-value {
  background:linear-gradient(0deg, rgba(222,231,0,1) 17%, rgba(255,250,146,1) 48%, rgba(247,247,247,0.16290266106442575) 61%, rgba(255,235,0,1) 64%);;
  float:left;
  width: 280px;
  height: 30px;
  background-size:cover;
  background-repeat:no-repeat;
    border-radius: 10px; 
   
 background-size: 100% 100%;
 
}
/* THE END */
  </code></pre>
