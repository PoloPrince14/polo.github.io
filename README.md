<!DOCTYPE html>
<html lang="en">


<head>
  <meta charset="UTF-8">
  <title>CSS Flag Project</title>
  <style>
    /* Write your CSS Code here */


.flag {
  width: 900px;
  height: 600px;
  background-color: #C8102E;
  position: relative;
}




.flag > div {
  background-color: #0033A0;
  height: 200px;
  width: 100%;
  position: absolute;
  top: 200px;
}




.flag > div > div {
  background-color: white;
  border-radius: 50%;
  width: 200px;
  height: 200px;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
}
   
  </style>
</head>
<body>
  <div class="flag">
    <p>The Flag</p>
    <div>
      <div>
     <p>of Laos</p>
      </div>
    </div>
  </div>
</body>


</html>
