---
title: Lab Members
icon: fa-users
order: 3
---
<head>
<style>
div.gallery {
  border: 1px solid #ccc;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: auto;
}

div.desc {
  padding: 15px;
  text-align: center;
}

* {
  box-sizing: border-box;
}

.responsive {
  padding: 0 6px;
  float: left;
  width: 24.99999%;
}

@media only screen and (max-width: 700px) {
  .responsive {
    width: 49.99999%;
    margin: 6px 0;
  }
}

@media only screen and (max-width: 500px) {
  .responsive {
    width: 100%;
  }
}

.clearfix:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<h2>Responsive Image Gallery</h2>
<h4>Resize the browser window to see the effect.</h4>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="img_5terre.jpg">
      <img src="/assets/images/tom_nm_final_crop.jpg" alt="Tom" width="600" height="400">
    </a>
    <div class="desc">Tom Miller</div>
  </div>
</div>


<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="img_forest.jpg">
      <img src="/assets/images/tingfa_dong.jpg" alt="Tingfa" width="600" height="400">
    </a>
    <div class="desc">Tingfa Dong</div>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="img_lights.jpg">
      <img src="/assets/images/MDonald.jpg" alt="Marion" width="600" height="400">
    </a>
    <div class="desc">Marion Donald</div>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="/assets/images/josh_fowler.jpg">
      <img src="/assets/images/josh_fowler.jpg" alt="Josh" width="600" height="400">
    </a>
    <div class="desc">Josh Fowler</div>
  </div>
</div>

<div class="clearfix"></div>

<div style="padding:6px;">
  <p>This example use media queries to re-arrange the images on different screen sizes: for screens larger than 700px wide, it will show four images side by side, for screens smaller than 700px, it will show two images side by side. For screens smaller than 500px, the images will stack vertically (100%).</p>
  <p>You will learn more about media queries and responsive web design later in our CSS Tutorial.</p>
</div>

</body>