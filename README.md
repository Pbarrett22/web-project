# web-project
<head>
<title>My web page projet/about</title>
  
</head>
<body>
<div class="container">
  <nav>
  <ul class="bar">
    <li><a href="#"class="active">Home</a></li>
    <li><a href="#"class="active">About</a></li>
    <li><a href="#" class="active">Contact</a></li>
  </ul>
  </nav>
</div>
  .bar {
  background-color: rgb(102, 255, 255);
  width: 100%;
  height: 40px;
  display: flex;
  list-style: none;
  padding: 0;
}

.bar li {
  height: 100%;
  width: 100px;
  border-right: 1px solid rgb(0, 72, 186);
}

.bar li a {
  color: blue;
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none;
}

.bar li a:hover {
  background-color: rgb(0, 21, 16);
}

.bar li a.active {
  background-color: rgb(255, 255, 255);
  color: white;
}

</body>
