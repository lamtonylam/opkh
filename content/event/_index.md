---
title: Tulevat tapahtumat

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 3

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""
---
Tänään on:
<h3> <span id="date"></span></h3>
<script type="text/javascript" language="javascript">
n =  new Date();
y = n.getFullYear();
m = n.getMonth() + 1;
d = n.getDate();
document.getElementById("date").innerHTML = d  + "." + m + "." + y;
</script>