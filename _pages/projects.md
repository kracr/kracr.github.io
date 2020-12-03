---
title: "KRaCR Lab - Publications"
layout: gridlay
excerpt: "KRaCr Lab -- Publications."
sitemap: false
permalink: /projects/
---

# Projects






<button class="collapsible" id="1">Open Collapsible</button>
<div class="content">
  <p>XYZ..................................................................................
XYZ............................................................................................
XYZ...........................................................................................</p>
</div>


<button class="collapsible">Open Section 1</button>
<div class="content">
  <p>XYZ</p>
</div>

<button class="collapsible">Open Section 2</button>
<div class="content">
  <p>XYZ</p>
</div>

<button class="collapsible">Open Section 3</button>
<div class="content">
 <p>XYZ</p>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    } 
  });
}
</script>

</body>
</html>

