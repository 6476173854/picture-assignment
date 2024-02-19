<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
  margin: 0;
  border: 0;
  font-family: 'Roboto', sans-serif;
}

.header {
  display: grid;
  grid-template-columns: 1fr;
  align-items: center;
  background-color: cadetblue;
}
.header1 {
  display: table;
  grid-template-columns: 1fr;
  align-items:center;
  background-color: rgb(109, 67, 185);
  text-align: center;
}

.title {
  padding: 50px 25px;
  text-align: center;
}

h1 {
  font-size: 3rem;
  margin: 0;
}
h7{
    
    text-align: start;
}

h4 {
  font-size: 1.5rem;
  font-weight: 300;
}

img {
  display: block;
}

@media (min-width: 960px) {
  .header {
    grid-template-columns: repeat(2, 1fr);
  }
}
    </style>
</head>
<body>
  <header class="header">
    <div class="title">
      <h1>Picture This!</h1>
      <h4>My DHABA</h4>
    </div>
    <img src="images/mirchi dhaba.jpg" alt="placeholder">
    

  </header>
  <header1 class="header1">
    <div class="title">
      <h7>Picture This!</h7>
      <h5>My DHABA</h5>
    </div>
    <img src="images/mirchi dhaba.jpg" alt="square">
    

  </header1>
</body>

</html>
