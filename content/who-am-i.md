---
title: "Who Am I"
date: 1995-10-15T04:15:00+01:00
---

Hi! My name is Bogdan Habić and I was born <span id="birth-time-ago"></span> ago.

In this time I had a lot of hobbies of which a rare few survived.

<script type="text/javascript">
  var x = new Date(1995, 10, 15, 4, 15, 0, 0); var birthTimeAgo = document.getElementById('birth-time-ago'); var epoch = new Date('1970-01-01 00:00:00-0600'); var tick = function(){ var y = new Date(); var z = new Date(y - x); var diff_years = z.getYear() - epoch.getYear(); var diff_month = z.getMonth() - epoch.getMonth(); var diff_days = z.getDate() - epoch.getDate(); var diff_hours = z.getHours() - epoch.getHours(); var diff_minutes = z.getMinutes() - epoch.getMinutes(); var diff_seconds = z.getSeconds() - epoch.getSeconds(); birthTimeAgo.innerHTML = diff_years + " years, " + diff_month + " month" + (diff_month == 1 ? "" : "s") + ", " + diff_days + " day" + (diff_days == 1 ? "" : "s") + ", " + diff_hours + " hour" + (diff_hours == 1 ? "" : "s") + ", " + diff_minutes + " minute" + (diff_minutes == 1 ? "" : "s") + ", " + diff_seconds + " second" + (diff_seconds == 1 ? "" : "s"); };setInterval(tick, 1000); tick();
</script>