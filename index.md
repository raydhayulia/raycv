<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel='stylesheet' href='https://fonts.googleapis.com/css?family=Roboto'>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <title>CV WITH HTML</title>
    <style>
body{
        background-color: pink;
        font-family: monospace;
        font-size: 45px;
        text-align: left;

      }
#container {
        background-color: white;
      padding: 100px 100px 100px 100px;
      text-align: left;
    }
header{
  font-style: "Roboto";
  padding: 1em;
  color: black;
  clear: left;
  text-align: center;
  font-size: 35px;
}
footer{
  padding: 1em;
  color: black;
  background: pink;
  margin-top: 1em;
  text-align: center;
  font-size: 16px;

}
nav{
        background-color: white;
        color: #ff00bf;
        float: left;
        max width: 160px;
        padding: 1em;
        margin: 0;
        font-size: 18px;
        text-align: left;

      }
nav ul {
  list-style-type: none;
  padding: 16;
  text-align: left;
}
nav ul a{
  text-decoration: none;
  text-align: left;
}
article{
  background-color: white;
  color: pink ;
  border-left: 170px;
  border-left: 1px solid grey;
  padding: 1em;
  overflow: hidden;
  font-size: 20px;
  text-align: left;
  border-left: 170px;
}
form{
  font-style: "Roboto";
  padding: 1em;
  clear: left;
  text-align: left;
  font-size: 20px;
  float: left;
  max width: 160px;

}

</style>
</head>

<body>
  <header>
  <h1> WELCOME TO MY BLOG </h1>
</header>
<header style="background-image:url('atas.jpg')">
  <div class="w3-bar w3-pink" padding=1em>
    <button class="w3-bar-item w3-button" onclick="openTab('My Blog')">My Blog</button>
    <button class="w3-bar-item w3-button" onclick="openTab('About Me')">About Me</button>
    <button class="w3-bar-item w3-button" onclick="openTab('Be My Friend')">Be My Friend</button>

</div>
<div id="My Blog" class="w3-container tab">
<nav>
<header>
  <h1>Business Model Canva</h1>
</header>
  <h4>Bisnis Model Canvas adalah model bisnis yg terdiri dari 9 blok area aktivitas bisnis, yang memiliki tujuan memetakan strategi untuk membangun bisnis yang kuat, bisa memenangkan persaingan dan sukses
     dalam jangka panjang. Bisnis Model Canvas
    ini memiliki ciri khas dengan 9 blok model yang jika disatukan akan menjadi satu kesatuan bisnis:</h4>

</nav>
</div>

<div id="About Me" class="w3-container tab">
<header>
<h1>LET'S MEET RAYDHA YULIA!</h1>
</header>
<nav>
  <ul>
    <li><a><img src="ray.jpg" alt="width=500px"height=250px></a></li>
    <li><a>RAYDHA YULIA</a></li>
    <li><a>Institut Teknologi Kalimantan</a></li>
    <li><a>Rantau Panjang, 14 November 1997</a></li>
    <li><a>Jalan Bukit Niaga RT. 17 NO. 19, Pasar Baru</a></li>
    <li><a>Islam</a></li>
    <li><a>Balikpapan</a></li>
    <li><a>Minat: </a></li>
    <li><a>• Fashion </a></li>
    <li><a>• Industri Kreatif</a></li>
    <li><a>• Public Relation</a></li>
    <li><a>• UI/UX Designer</a></li>
    <li><a>• Content Creator</a></li>
    <li><a>__________________________________</a></li>


</ul>
</nav>

<article>
  <h2>Riwayat Pendidikan </h2>
  <p> • TK 10 November - 2002-2004</p>
  <P> • SD 016 Balikpapan - 2004-2010</P>
  <p> • SMP 2 Balikpapan - 2010-2013</p>
  <p> • SMA 1 Balikpapan - 2013-2016</p>

  <h2> Riwayat Pekerjaan </h2>
  			<table width="900px">
  				<tbody>
  			<tr><h3>
  						<td width="50%">Zetizen Kaltim Post</td>
  						<td width="1%">:</td>
  						<td> 2016-sekarang </td>
  					</tr>
  			<tr>
  						<td>Public Relation Kelasin Indonesia</td>
  						<td>:</td>
  						<td> 2018-sekarang</td>
  </tr>
  <h3>
  </tr>
  <tbody>
  </table>
<h2> Pengalaman Organisasi </h2>
<p>• Anggota Public Relation Acara ITK Innovation 2017 </p>
<p>• Anggota Genbi (Generasi Baru Indonesia)</p>
<p>• Anggota HIMA HUMAS 2018</p>
<h2> Keahlian </h2>
<p> • Miscrosoft Word </p>
<p> • Menulis </p>
<p> • UI/UX Designer </p>
<p> • Public Relation </p>
<p> • Programmer </p>
<p> • Fotografi </p>
<p> • Event Organizer </p>
<p> • Content Creator </p>



</article>

</div>
<script>
function openTab(tabName) {
    var i;
    var x = document.getElementsByClassName("tab");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";
    }
    document.getElementById(tabName).style.display = "block";
}

</script>
<div id="Be My Friend" class="w3-container tab">
<form action="/action_page.php" target="_blank">
      <div class="form">
        <label>Name</label>
        <input class="w3-input w3-border" type="text" required name="Name">
      </div>
      <div class="w3-section">
        <label>Email</label>
        <input class="w3-input w3-border" type="text" required name="Email">
      </div>
      <div class="w3-section">
        <label>Message</label>
        <input class="w3-input w3-border" required name="Message">
      </div>

  <button onclick="myFunction()">Send</button>
  <script>
function myFunction() {
alert("Hello Teman!");
}

</script>
    </form><br>

  </div>
  <footer img src="background-image:url('atas.jpg')">
    <p>Find me on social media.</p>
    <a href = "https:/www.facebook.com/raydhayulia"><i class="fa fa-facebook-official w3-hover-opacity"></i></a>
    <a href = "https:/www.instagram.com/raydhayulia"><i class="fa fa-instagram w3-hover-opacity"></i></a>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <a href = "https:/www.twitter.com/rayulia"><i class="fa fa-twitter w3-hover-opacity"></i></a>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
    <p>Powered by <a>Raydha Yulia</a></p>

  </footer>
</body>
</html>
