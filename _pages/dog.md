---
layout: dog
title: dog
id: dog
permalink: /dog
---

# dog

This is Lulu. 

<script>
var img_name = new Array("../assets/1.jpg", "../assets/2.jpg", "../assets/3.jpg", "../assets/4.jpg", "../assets/5.jpg");

var l = img_name.length;

// pfft who needs WebCrypto API...
var rnd_no = Math.floor(l*Math.random());
var img = document.createElement("img");
img.src = img_name[rnd_no];
document.body.appendChild(img);
</script>