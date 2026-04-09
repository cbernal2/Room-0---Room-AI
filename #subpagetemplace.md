<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1" /> 
	<title> writehere - Room 0</title>
	<link rel="stylesheet" href="../../../style.css">
</head> 

<!-- "back to top" button anchor tag -->
 <body> 
	<a id="top"></a>

<!------------ HEADER ------------->
<header> 
	<div class="header-content">
	<div class="header-site-name">
			<h1><a href="../../../index.html">Room Ø</a></h1>
		</div>
	<div class="header-nav">
	<!-- this aligns the header with the title on the left -->
	<nav> <!-- NAVIGATION BAR --->
		<ul> 
			<li><a href="../../../index.html"></a></li>
			<li><a href="../../../about.html">About</a></li>
			<li><a href="../../../collections.html" class="active">Home</a></li> <!-- !CHANGE ACTIVE ON EACH PAGE! -->>Collections</a></li>
			<!--<li><a href="../../../az.html">A-Z</a></li>-->
		</ul>
	</nav> <!-------------------->
</div>
</div>
</header>
<!---------------------------------->

 <main>

<div style="text-align: center">
	<h3>.  </h3>
</div>

<br><br><br> 


<!--- IMAGE -->
<div style="text-align: center;">
	<img src="../../../images/ephemera_goodluck.jpeg" alt="Letter from Neighbours" style="width: 400px; height: auto; border-radius: 30px; transform: rotate(270deg)">
	<figcaption></figcaption> 
</div>
<!------------>
	


<!----- AI Archvist Toggle Button -->
<div class="toggle-button">
	<button  id="toggleBtn" onclick="toggleParagraph()"> AI Archivist</button>
</div>
<!----------------------------------->
	
<br><br> 

<!------ This is the Human Archivist initial paragraph-------->
<div id="p1" class="paragraph active-paragraph"> 

<div class="quote-section">
  <span class="quote-label">quote title</span>

<blockquote>
	quote here

</blockquote>

<p> main text here</p>

</div>




<!----------------------------------------------------------->


<!----------------HUMAN METADATA TABLE ----------------------->
<div style="text-align: center;">
      <h3>Artifact Metadata</h3>
    </div>

  <table class="table">
  <!-- table headings -->

    <tr>
      <th>Type</th>
      <th>Description</th>
   </tr>
<!-------------------->
  	<tr>
      <td>Name</td>
      <td></td>
    </tr>
   <tr>
    <td>Collection</td>
    <td></td>
    </tr>
  <tr>
    <td>Origin</td>
    <td></td>
  </tr>
  <tr>
    <td>Date</td>
    <td></td>
  </tr>
  <tr>
    <td>Location</td>
    <td></td>
  </tr>
  <tr>
    <td>Condition</td>
    <td> </td>
  </tr>
  <tr>
    <td>Colour</td>
    <td> </td>
  </tr>
  <tr>
    <td>Tags</td>
    <td>
      <a> </a>
    </td>
  </tr>

  </table>
<!-------------------------------- --> 

</div>


<!-------- this is the AI Archivist paragraph---------------->
<div id="p2" class=paragraph> 

	<div style="text-align:center;">
		<h2> AI Generated: "The Sweatshirt That Stayed"</h2>
		<br><br>
	</div>

	<p> here </p>


<!-------------AI ARCHIVIST METADATA TABLE----------------->
	<div style="text-align: center;">
      <h3>Artifact Metadata</h3>
    </div>

  <table class="table">
  <!-- table headings -->

    <tr>
      <th>Type</th>
      <th>Description</th>
   </tr>
<!-------------------->
  	<tr>
      <td>Artifiact ID</td>
      <td></td>
    </tr>
   <tr>
    <td>Title</td>
    <td></td>
    </tr>
  <tr>
    <td>Category</td>
    <td></td>
  </tr>
  <tr>
    <td>Date</td>
    <td></td>
  </tr>
  <tr>
    <td>Physical Description</td>
    <td></td>
  </tr>
  <tr>
    <td>Condition</td>
    <td></td>
  </tr>
  <tr>
  

  </table>

</div>

<!----------------------------------------------------------->

<!--- JS to control toggle button --------->
<script>
  function toggleParagraph() {
    const p1 = document.getElementById("p1");
    const p2 = document.getElementById("p2");
	const button = document.getElementById("toggleBtn");

    if (p1.classList.contains("active-paragraph")) {
      p1.classList.remove("active-paragraph");
      p2.classList.add("active-paragraph");

	  button.textContent = "View Human Archivist";
    } else {
      p2.classList.remove("active-paragraph");
      p1.classList.add("active-paragraph");

	  button.textContent = "View AI Archivist";
    }
  }
</script>
<!-------------------------------------------->





</main>



<!-- "back to top" button --->
<a href="#top">↑ Back to Top</a>

<!------------- FOOTER -------------->
<footer> 
<div class="footer-content">

<nav class="footer-nav"> 
	<a href="../../../index.html">Home</a>
	<a href="../../../about.html">About</a>
	<a href="../../../collections.html">Collections</a>
	<a href="../../../az.html">A-Z</a>
</nav>

<div class="footer-site-name">
	<h1><a href="../../../index.html">Room Ø</a></h1>
</div>
</div>


</footer> 
<!----------------------------------->


<!-- bottom center copyright --->
<p class="footer-copy">&copy; 2025 Room 0. All rights reserved.</p>
<!------------------------------------>


</body>
</html> 