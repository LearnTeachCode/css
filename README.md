# css
Save the following code inside your **index.html** file.
###index.html
```html
<!DOCTYPE html>
<html>
<head>
<title>The Awesomeness of HTML and CSS!</title>
<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
<header id="site-header">
	<ul class="navigation">
		<li><a href="#">Home</a></li>
		<li><a href="#">About</a></li>
		<li><a href="#">Blog</a></li>
	</ul>
	<h1>HTML and CSS are Awesome</h1>
	<div class="banner">
		<img src="html-rocks.jpg">
	</div>
</header>
<div id="content">
	<div id="main">
		<p>This is a paragraph about why HTML and CSS are so awesome. Add your reasons here!</p>
		<p>This is another paragraph with even more reasons why HTML and CSS are awesome.</p>
		<ul>
			<li>One cool thing about HTML</li>
			<li>Another cool thing about HTML</li>
			<li>And a third thing about HTML</li>
		</ul>
		<p>In conclusion, HTML and CSS are the coolest computer languages ever. Thanks for reading this informative article!</p>
		<div class="boxes">
			<div class="box">
				<h3>Box 1 Title</h3>
				<div class="desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce sit amet pulvinar diam, sit amet viverra erat. Maecenas vitae orci sit amet nulla sagittis luctus. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
				<div class="more"><a href="#">Read More</a></div>
			</div>
			<div class="box">
				<h3 class="title">Box 2 Title</h3>
				<div class="desc">Donec vel leo posuere ex pellentesque rhoncus. Etiam purus mauris, sagittis in cursus eu, finibus in eros. </div>
				<div class="more"><a href="#">Learn More</a></div>
			</div>
			<div class="box">
				<h3 class="title">Box 3 Title</h3>
				<div class="desc">Proin mollis pharetra rhoncus. Morbi condimentum egestas efficitur. Nam dapibus posuere ipsum a volutpat. Vivamus nibh augue, scelerisque vel velit a, consequat imperdiet tellus.</div>
				<div class="more"><a href="#">View More</a></div>
			</div>
		</div>
	</div>
	<div id="sidebar">
		<h2>More HTML and CSS Resources</h2>
		<ul>
			<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element">Mozilla Developer Reference on HTML</a></li>
			<li><a href="http://www.csszengarden.com/">CSSZenGarden</a></li>
			<li><a href="https://dash.generalassemb.ly/">DASH Interactive Tutorial by General Assembly</a></li>
		</ul>
	</div>
</div><!-- end of .wrapper -->
<footer>
	<p>Copyright My Name 2016 &copy;</p>
</footer>
</body>
</html>
```
