---
title: "Dum Du"
hidden: true
---

<h1>
  Dobrodosla!
</h1>

<h2 id="poruka">

</h2>
<pre id="message">
</pre>

<script type="text/javascript">
  var time = new Date();
  var poruka = document.getElementById('poruka');
  var message = document.getElementById('message');
  if(time.getHours() < 7 || time.getHours() > 10) {
    poruka.innerHTML = 'Nazalost trenutno nije vreme za dum dum! Vrati se kada bude!';
  } else {
    poruka.innerHTML = 'Bravo! Ispod mozes naci sledece tragove!';
    message.innerHTML = "kovan\n0xa302855e9801021ce43a69aeb4bca7cd8f5d5dbd";
  }
</script>