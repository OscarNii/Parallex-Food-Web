 ```
# Food Parallax

This is a simple parallax website that I created to demonstrate how to use the parallax effect in HTML and CSS. The website consists of a header, a navigation bar, a parallax section, and a footer.

## HTML

The HTML code for the website is as follows:

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<title>Food Parallax</title>
		<meta name="description" content="" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<link rel="stylesheet" href="app.css" />
	</head>
	<body>
		<header>
			<a href="#" class="logo">logo</a>
			<ul class="navlist">
				<li><a href="#home" class="Active">Home</a></li>
				<li><a href="#about">About</a></li>
				<li><a href="#product">Product</a></li>
				<li><a href="#contact">Contact</a></li>
			</ul>
		</header>
        <section class="parallax-home">
            <img src="Images/ice-cream-1274894_1280.png" alt="" id="">
        </section>

		<!-- <script src="" async defer></script> -->
	</body>
</html>
```

The HTML code is fairly straightforward. The `<head>` section contains the meta tags and the link to the CSS file. The `<body>` section contains the header, the navigation bar, the parallax section, and the footer.

## CSS

The CSS code for the website is as follows:

```css
body {
  margin: 0;
  padding: 0;
  font-family: sans-serif;
}

header {
  background-color: #000;
  color: #fff;
  padding: 10px;
}

.logo {
  font-size: 24px;
  font-weight: bold;
}

