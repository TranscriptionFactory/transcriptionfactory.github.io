---
layout: page
title: jstest
permalink: /jstest/
---

<html>
<style>
#myContainer {
  width: 400px;
  height: 400px;
  position: relative;
  background: yellow;
}
#myAnimation {
  width: 50px;
  height: 50px;
  position: absolute;
  background-color: red;
}
</style>
<body>

<p>
<button name = "button1">Click Me</button> 
</p>

<div id ="myContainer">
<div id ="myAnimation"></div>
</div>

<script type = "text/javascript" src = "assets/movingBox.js">
button1.onclick = myMove((jstest.md).document);
</script>

</body>
</html>

