---
title: Lab Members2
icon: fa-users
order: 5
---


<head>
<style>
/* Three columns side by side */
.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

/* Display the columns below each other instead of side by side on small screens */
@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

/* Add some shadows to create a card effect */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

/* Some left and right padding inside the container */
.container {
  padding: 0 16px;
}

/* Clear floats */
.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}
</style>
</head>
<body>

<div class="row">
  <div class="column">
    <div class="card">
      <img src="/assets/images/tom_nm_final_crop.jpg" alt="Tom" style="width:100%">
      <div class="container">
        <h2>Tom Miller</h2>
        <p class="title">PI</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>tom.miller@rice.edu</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="/assets/images/tingfa_dong.jpg" alt="tingfa_dong" style="width:100%">
      <div class="container">
        <h2>Tingfa Dong</h2>
        <p class="title">Visiting Scholar</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="/assets/images/MDonald.jpg" alt="Marion" style="width:100%">
      <div class="container">
        <h2>Marion Donald</h2>
        <p class="title">Graduate Student</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="card">
      <img src="/assets/images/josh_fowler.jpg" alt="Josh" style="width:100%">
      <div class="container">
        <h2>Josh Fowler</h2>
        <p class="title">Graduate Student</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
</div>
  </body>