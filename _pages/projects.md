---
title: "KRaCR Lab - Publications"
layout: gridlay
excerpt: "KRaCr Lab -- Publications."
sitemap: false
permalink: /projects/
---

# Projects


<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
  background-color: white;
  color: purple;
  cursor: pointer;
  padding:1px 20px 1px 20px;
  width: 100%;
  text-align: left;
  font-size: 25px;
 border-radius: 8px;
border-style:none;
}

.active, .collapsible:hover {
color: #800080;
background-color:#f5f5f0
}

.collapsible:after {
  content: '\002B';
border-style:none;
color:#800080;
  font-weight: bold;
  float: right;
}

.active:after {
  content: "\2212";
color: purple;

}

.content {
  padding: 5px 30px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
  background-color: white;
  color:purple;
width: 100%;
}
</style>
</head>
<body>




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

