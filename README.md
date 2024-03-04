# web-project
<head>
<title>My web page projet/home</title>
  
</head>
<body>
<span class="container">
  <nav>
  <ul class="bar">
    <a href="#"class="active">Home</a></li>
    <a href="#"class="active">About</a></li>
    <a href="#" class="active">Contact</a></li>
  </ul>
  </nav>
</span>
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
<p>welcome to my web page project.</p>
</body>
