<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Januth Intro</title>
<style>
body{
  margin:0;
  height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);
  font-family:Arial, sans-serif;
  color:white;
  overflow:hidden;
}

.container{
  text-align:center;
  animation: fadeIn 2s ease-in-out;
}

h1{
  font-size:50px;
  animation: slideDown 2s ease;
}

p{
  font-size:24px;
  opacity:0;
  animation: fadeUp 2s ease forwards;
  animation-delay:2s;
}

.tag{
  margin-top:10px;
  font-size:20px;
  color:#00eaff;
  opacity:0;
  animation: fadeUp 2s ease forwards;
  animation-delay:4s;
}

@keyframes fadeIn{
  from{opacity:0}
  to{opacity:1}
}

@keyframes slideDown{
  from{transform:translateY(-80px); opacity:0}
  to{transform:translateY(0); opacity:1}
}

@keyframes fadeUp{
  from{transform:translateY(40px); opacity:0}
  to{transform:translateY(0); opacity:1}
}
</style>
</head>

<body>

<div class="container">
  <h1>Hello 👋</h1>
  <p>My Name is <b>Januth</b></p>
  <div class="tag">20 Years Old • Software Engineer 💻</div>
</div>

</body>
</html>
