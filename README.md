<h1>Tervetuloa</h1>

<!-- Painike -->
<button id="pop-up-nappi">Näytä viesti</button>

<!-- Itse pop-up (aluksi piilotettu) -->
<div id="viesti-box" style="display:none; border:1px solid #000; padding:20px; position:fixed; top:50%; left:50%; transform:translate(-50%, -50%); background:white;">
  <p>Tämä on viesti sivulta ilari2024.github.io</p>
  <button onclick="document.getElementById('viesti-box').style.display='none'">Sulje</button>
</div>

<script>
  document.getElementById('pop-up-nappi').onclick = function() {
    document.getElementById('viesti-box').style.display = 'block';
  };
</script>
