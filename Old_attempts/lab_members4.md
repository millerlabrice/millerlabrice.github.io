---
title: Lab Members4
icon: fa-users
order: 3
---
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.container {
  position: relative;
  width: 50%;
}

.image {
  display: block;
  width: 100%;
  height: auto;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: .5s ease;
  background-color: #008CBA;
}

.container:hover .overlay {
  opacity: .5;
}

.text {
  color: white;
  font-size: 12px;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  text-align: center;
}
</style>
</head>
<body>

<h2>Fade in Overlay</h2>
<p>Hover over the image to see the effect.</p>

<div class="container">
  <img src="/assets/images/josh_fowler.jpg" alt="Avatar" class="image" alt="Josh" width="600" height="400">
  <div class="overlay">
    <div class="text">Josh is interested in using demography to understand how context-dependent mutualisms contribute to setting species range limits and how they help hosts cope with environmental variability. Josh is using grasses and fungal endophytes as a study system.</div>
  </div>
</div>

</body>