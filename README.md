# front-sass-css3-html5-jquery

## Intro

- Demo Project - https://www.joystick.com.mx/udemy/

## Software and Resources

- Sublime Text 3 - https://www.sublimetext.com/3
- Prepros - https://prepros.io/downloads
- Emmet
- Web browsers

- Sublime Text 3 Package Control - https://packagecontrol.io/installation

```
import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

Inside Sublime Text 3 > View > Show Console > Paste the code and press `Enter`

Go to `Package Control` under Sublime Text > Preferences > Package Control

Insert:

`Package Control: Install Package`

Look for `Emmet` and install it

Restart Sublime text

Open a new file, select `HTML` in the right and lower part

Try Emmet, write `.myclass` and by pressing `tab` it will create a div automatically

```html
<div class="myclass"></div>
```

Try Emmet, write `#myid` and by pressing `tab` it will create a div automatically

```html
<div id="myid"></div>
```

Try Emmet, write `span` and by pressing `tab` it will create a `span` automatically

```html
<span></span>
```

Try Emmet, write `p` and by pressing `tab` it will create a `p` automatically

```html
<p></p>
```

Try Emmet, write `div` and by pressing `tab` it will create a `div` automatically

```html
<div></div>
```

Try Emmet, write `img` and by pressing `tab` it will create a `img` automatically

```html
<img src="" alt="">
```

Try Emmet, write `link` and by pressing `tab` it will create a `link` automatically

```html
<link rel="stylesheet" href="">
```

Try Emmet, write `script` and by pressing `tab` it will create a `script` automatically

```html
<script></script>
```

Try Emmet, write `a` and by pressing `tab` it will create an `a` automatically

```html
<a href=""></a>
```

Try Emmet, write `p.my-paragraph` and by pressing `tab` it will create an `p` automatically with that class

```html
<p class="my-paragraph"></p>
```

Try Emmet, write `a#my-id` and by pressing `tab` it will create an `a` automatically with that id

```html
<a href="" id="my-id"></a>
```

Try Emmet, write `p{"This is my text"}` and by pressing `tab` it will create an `p` automatically with that text

```html
<p>"This is my text"</p>
```

Try Emmet, write `ul>li*3` and by pressing `tab` it will create an `ul` automatically with that quantity of elements

```html
<ul>
    <li></li>
    <li></li>
    <li></li>
  </ul>
```

Try Emmet, write `ul>li{$}*5` and by pressing `tab` it will create an `ul` automatically with that quantity of enumerated elements

```html
<ul>
  <li>1</li>
  <li>2</li>
  <li>3</li>
  <li>4</li>
  <li>5</li>
</ul>
```

Try Emmet, write `nav>ul>li>a*5` and by pressing `tab` it will create that automatically 

```html
<nav>
  <ul>
    <li>
      <a href=""></a>
      <a href=""></a>
      <a href=""></a>
      <a href=""></a>
      <a href=""></a>
    </li>
  </ul>
</nav>
```

## Project Structure & File's Organization

- Demo Project - https://www.joystick.com.mx/udemy/

- Recommended Structure

```
project-folder
  > css
  > favicon
  > fonts
  > images
  > js
  > processes
  - contact.html
  - contact.pdf
  - home.pdf
  - index.html
  - portfolio.html
  - portfolio.pdf
  - prepos-6.config
  - preview.html
```

Open Prepros, drag and drop the folder of the project

Open Sublime, drag and drop the folder of the project

Set up Sublime View

View > Side Bar > Show Open Files

View > Layout > Columns: 2

project_folder > `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Test</title>
</head>
<body>
  <h1>Hello World!</h1>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elilt. Officiis exercitationem modi reiciendis, dignissimos culpa sequi eveniet ab nesciunt commodi soluta, quia ipsum reprehenderit vero magnam, tempora aut atque neque perferendis.</p>
  <br>
  <h2>Headline</h2>
</body>
</html>
```

## HTML5, CSS3, SASS

project_folder > `index.html`

### Main HTML5 Tags 

- https://placeholder.com/

```html
<div class="container">
  <div class="row">
    <div class="col">
      
        <!-- STRUCTURALS -->
        STRUCTURAL ELEMENTS
        <br><br>
        <nav>
        	NAV: Used for Navigation Bars 
        </nav>

        <header>
        	HEADER: Used for Headlines of Elements
        </header>

        <section>
        	SECTION: Used to divide, is a container
        </section>

        <div>
        	DIV: used to divide and structure, is a container
        </div>


        <!-- TEXTS & IMAGES -->
       	<p>
       		P: Texts or Content
       		<br><br>
       		<strong>Block Elements</strong> are the ones that cover all the width of the screen or its father container
       		<br><br>
       		<strong>Inline</strong> are the ones that just cover the space needed to be shown.
       		Examples: span, small, sub, sup, a, strong, em, i
       	</p>

       	<a href="">
       		A: Link
       	</a>

       	<br>

       	<span>
       		SPAN: Small blocks of text
       	</span>

       	<br>

		<small>
			SMALL: Small text
		</small>

		<br>

		H2O
		H<sup>2</sup>O
		H<sub>2</sub>O

		<br>

		<strong>STRONG: Bold Text</strong>

		<br>

		<i>I: Italic Text</i>

		<br>

		<em>EM: Italic Text</em>

		<br>

		NUMBERED LISTS
		<ol>
			<li>One</li>
			<li>Two</li>
			<li>Three</li>
		</ol>

		BULLET LISTS
		<ul>
			<li>One</li>
			<li>Two</li>
			<li>Three</li>
		</ul>

		<img src="https://via.placeholder.com/300" alt="Text Alternative">


		<table>
			<thead>
				<tr>
					<th>Name</th>
					<th>Age</th>
					<th>Profession</th>
				</tr>
			</thead>

			<tbody>
				<tr>
					<td>Roberto Orozco</td>
					<td>23 years</td>
					<td>Developer</td>
				</tr>

				<tr>
					<td>John Doe</td>
					<td>25 years</td>
					<td>Designer</td>
				</tr>
			</tbody>
		</table>

		<style>
			body {
					background-color:grey;
			}
			input, textarea, select, option {
				width: 100%
			}
		</style>

		<br><br>

		<!-- FORMS -->
		FORMS
		<br>

		<form action="">

			Text Type
			<input type="text">

			Name Type
			<input type="name">

			Email Type
			<input type="email">

			Number Type
			<input type="number">

			Color Picker Type
			<input type="color">

			Checkbox 
			<label for="checkboxes">1st checkbox</label>
			<input type="checkbox" value="1st checkbox" id="checkboxes">
			<input type="checkbox" value="1st checkbox" id="checkboxes">
			<input type="checkbox" value="1st checkbox" id="checkboxes">
			<input type="checkbox" value="1st checkbox" id="checkboxes">

			<textarea name="" id="" cols="30" rows="10"></textarea>

			<select name="" id="">
				<option value="">Option 1</option>
				<option value="">Option 2</option>
				<option value="" selected="">Option 3</option>
			</select>

			Radio Type
			<input type="radio">
			<input type="radio">
			<input type="radio">
			<input type="radio">


			Submit Type - Send the Form
			<input type="submit">

		</form>

		<button>This is a button</button>

		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
		<br>
```

### Main Properties and CSS3 Selectors

project_folder > `styles.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>CSS3 Intro</title>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
	
	<!-- Our Styles -->
	<link rel="stylesheet" href="css/styles.css">
</head>

<body>
	<h1>This will be huge!</h1>
	<p>This will be red</p>
	<a href="">This is a green link!</a>

	<div>
		<p>I'm inside a Pink Container</p>
	</div>

	<div class="myclass">
		<p>I'm inside a Container with Class!</p>
	</div>

	<div id="identifier">
		White Text!
		<p>I'm inside a Container with Unique Id</p>
	</div>

</body>
</html>
```

project_folder > css > `styles.css`
```css

body 
{
	padding: 50px;
}



/*
STRUCTURE OF CSS3
selector
{
	attribute: value;
	attribute: value;
}

USE ColorPicker
cmd+shift+c
*/

h1
{
	font-size: 60px;
}

p
{
	color: red;
}

a
{
	color: green;
}

div
{
	background-color: #eb6;
}

div p 
{
	color: blue;
}

.myclass
{
	background-color: #91D4FF;
	padding: 15px;
	text-align: center;
	border-radius: 10px;
	margin: 10px 0px;
}

.myclass p 
{
	font-size: 28px;
	color: #91FFFF;
}

#identifier 
{
	background-color: #AABBCC;
	color: white;
	padding: 50px;
	text-align: center;
	border-radius: 20px;
}

#identifier p
{
	color: #FFE2D1FF;
}
```

### Intro to SASS

project_folder > `styles.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>CSS3 Intro</title>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
	
	<!-- Our Styles -->
	<link rel="stylesheet" href="css/styles2.css">
</head>

<body>
	<h1>This will be huge!</h1>
	<p>This will be red</p>
	<a href="">This is a green link!</a>

	<div>
		<p>I'm inside a Pink Container</p>
	</div>

	<div class="myclass">
		<p>I'm inside a Container with Class!</p>
	</div>

	<div id="identifier">
		White Text!
		<p>I'm inside a Container with Unique Id</p>
	</div>

	<!-- Separation -->
	<div class="one">
		<div class="two">
			<div class="three">
				<div class="four">
					<h3 class="five">I'm a h3</h3>
					<p class="six"> Hello World, click <a href="" class="seven">here</a></p>
				</div>
			</div>
		</div>
	</div>

</body>
</html>
```

project_folder > css > `styles2.sass`
```sass
$base: #AABBCC

body
	padding: 50px

h1
	font-size: 60px

p 
	color: red

a 
	color: green 

div 
	background-color: #eb6
	p 
		color: blue

.myclass
	background-color: #91D4FF
	padding: 15px
	text-align: center
	border-radius: 10px
	margin: 10px 0px
	p 
		font-size: 28px
		color: #91FFFF

#identifier
	background-color: $base
	color: white
	padding: 50px
	text-align: center
	border-radius: 20px
	p 
		color: white

.one
	margin: 50px 0px
	padding: 20px
	background-color: transparentize(black, .9)
	.two
		padding: 20px
		background-color: transparentize(black, .7)
		.three
			padding: 20px
			background-color: transparentize(black, .5)
			.four
				padding: 20px
				background-color: transparentize(black, .3)
				.five
					color: white
					text-align: center
					font-size: 40px
				.six
					color: white 
					.seven
						color: white
						text-decoration: underline
						font-weight: bold
```

## Home & Company Section

### General HTML5 Structure, Meta Tags & Meta Viewport

project_folder > `index.html`

```html
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<title>Blackparadox</title>

	<!-- SEO natural -->
	<meta name="author" content="Joystick">
	<meta name="copyright" content="&copy; Joystick 2017. Todos los derechos reservados.">
	<meta name="email" content="hellow@joystick.com.mx">
	<meta name="robots" content="index,follow">
	<meta name="description" content="Expertos en fotografía, retratamos los momentos que siempre quieres conservar contigo, con más de 15 años de experiencia en crear recuerdos inolvidables">
	<meta name="keywords" content="foto, fotografía, cámara, digital, agencia, recuerdos, video, eventos, quince años, bodas, aniversario">

	<!-- Responsividad -->
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0">
	


	
</head>
<body>





	
</body>
</html>
```

### Adding Social Cards for Facebook & Twitter

project_folder > `index.html`

```html
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<title>Blackparadox</title>

	<!-- SEO natural -->
	<meta name="author" content="Joystick">
	<meta name="copyright" content="&copy; Joystick 2017. Todos los derechos reservados.">
	<meta name="email" content="hellow@joystick.com.mx">
	<meta name="robots" content="index,follow">
	<meta name="description" content="Expertos en fotografía, retratamos los momentos que siempre quieres conservar contigo, con más de 15 años de experiencia en crear recuerdos inolvidables">
	<meta name="keywords" content="foto, fotografía, cámara, digital, agencia, recuerdos, video, eventos, quince años, bodas, aniversario">

	<!-- Responsividad -->
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0">

	<!-- Social Cards -->
	<meta property="og:url" content="https://www.blackparadox.com">
	<meta property="og:type" content="website">
	<meta property="og:title" content="Blackparadox - Fotografía">
	<meta property="og:description" content="Expertos en fotografía, retratamos los momentos que siempre quieres conservar contigo, con más de 15 años de experiencia en crear recuerdos inolvidables">
	<meta property="og:image" content="https://www.blackparadox.com/images/logo_blackparadox.svg">
	


	
</head>
<body>





	
</body>
</html>
```

### Implementing Bootstrap 4 from CDN

project_folder > `index.html`

```html
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<title>Blackparadox</title>

	<!-- SEO natural -->
	<meta name="author" content="Joystick">
	<meta name="copyright" content="&copy; Joystick 2017. Todos los derechos reservados.">
	<meta name="email" content="hellow@joystick.com.mx">
	<meta name="robots" content="index,follow">
	<meta name="description" content="Expertos en fotografía, retratamos los momentos que siempre quieres conservar contigo, con más de 15 años de experiencia en crear recuerdos inolvidables">
	<meta name="keywords" content="foto, fotografía, cámara, digital, agencia, recuerdos, video, eventos, quince años, bodas, aniversario">

	<!-- Responsividad -->
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0">

	<!-- Social Cards -->
	<meta property="og:url" content="https://www.blackparadox.com">
	<meta property="og:type" content="website">
	<meta property="og:title" content="Blackparadox - Fotografía">
	<meta property="og:description" content="Expertos en fotografía, retratamos los momentos que siempre quieres conservar contigo, con más de 15 años de experiencia en crear recuerdos inolvidables">
	<meta property="og:image" content="https://www.blackparadox.com/images/logo_blackparadox.svg">
	
	<!-- Bootstrap 4 CDN -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css" integrity="sha384-PsH8R72JQ3SOdhVi3uxftmaW6Vc51MKb0q5P2rRUpPvrszuE4W1povHYgTpBfshb" crossorigin="anonymous">


	
</head>
<body>
	<div class="container">
		<div class="row">
			<div class="col">
				<h1>Hola mundo, tengo bootstrap!</h1>
			</div>
		</div>
	</div>




	<!-- Bootstrap 4 JS CDN -->
	<script src="https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js" integrity="sha384-vFJXuSJphROIrBnz7yo7oB41mKfc8JzQZiCq4NCceLEaO4IHwicKwpJf9c9IpFgh" crossorigin="anonymous"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/js/bootstrap.min.js" integrity="sha384-alpBpkh1PFOepccYVYDB4do5UnbKysX5WZXm3XxPqe5iKTfUKjNkCk9SaVuEZflJ" crossorigin="anonymous"></script>
	<script src="js/slippry.min.js"></script>
	
</body>
</html>
```

### Linking local style files

project_folder > `index.html`

```html
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<title>Blackparadox</title>

	<!-- SEO natural -->
	<meta name="author" content="Joystick">
	<meta name="copyright" content="&copy; Joystick 2017. Todos los derechos reservados.">
	<meta name="email" content="hellow@joystick.com.mx">
	<meta name="robots" content="index,follow">
	<meta name="description" content="Expertos en fotografía, retratamos los momentos que siempre quieres conservar contigo, con más de 15 años de experiencia en crear recuerdos inolvidables">
	<meta name="keywords" content="foto, fotografía, cámara, digital, agencia, recuerdos, video, eventos, quince años, bodas, aniversario">

	<!-- Responsividad -->
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0">

	<!-- Social Cards -->
	<meta property="og:url" content="https://www.blackparadox.com">
	<meta property="og:type" content="website">
	<meta property="og:title" content="Blackparadox - Fotografía">
	<meta property="og:description" content="Expertos en fotografía, retratamos los momentos que siempre quieres conservar contigo, con más de 15 años de experiencia en crear recuerdos inolvidables">
	<meta property="og:image" content="https://www.blackparadox.com/images/logo_blackparadox.svg">
	
	<!-- Bootstrap 4 CDN -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css" integrity="sha384-PsH8R72JQ3SOdhVi3uxftmaW6Vc51MKb0q5P2rRUpPvrszuE4W1povHYgTpBfshb" crossorigin="anonymous">

	<!-- Estilos -->
	<link rel="stylesheet" href="css/main.css">


	
</head>
<body>
	<div class="container">
		<div class="row">
			<div class="col">
				<h1>Hola mundo, tengo bootstrap!</h1>
			</div>
		</div>
	</div>




	<!-- Bootstrap 4 JS CDN -->
	<script src="https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js" integrity="sha384-vFJXuSJphROIrBnz7yo7oB41mKfc8JzQZiCq4NCceLEaO4IHwicKwpJf9c9IpFgh" crossorigin="anonymous"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/js/bootstrap.min.js" integrity="sha384-alpBpkh1PFOepccYVYDB4do5UnbKysX5WZXm3XxPqe5iKTfUKjNkCk9SaVuEZflJ" crossorigin="anonymous"></script>
	<script src="js/slippry.min.js"></script>
	
</body>
</html>
```
project_folder > css > `main.sass`

```sass
// Blackparadox
// Styles 2017
// Version: 1.0.1

// Color Variables

// General Styles

// Styles of Inputs, Textarea, Buttons

// Styles of NavBar
```

### Creating the NavBar

- https://getbootstrap.com/docs/4.2/layout/overview/

project_folder > `index.html`

```html
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<title>Blackparadox</title>

	<!-- SEO natural -->
	<meta name="author" content="Joystick">
	<meta name="copyright" content="&copy; Joystick 2017. Todos los derechos reservados.">
	<meta name="email" content="hellow@joystick.com.mx">
	<meta name="robots" content="index,follow">
	<meta name="description" content="Expertos en fotografía, retratamos los momentos que siempre quieres conservar contigo, con más de 15 años de experiencia en crear recuerdos inolvidables">
	<meta name="keywords" content="foto, fotografía, cámara, digital, agencia, recuerdos, video, eventos, quince años, bodas, aniversario">

	<!-- Responsividad -->
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0">

	<!-- Social Cards -->
	<meta property="og:url" content="https://www.blackparadox.com">
	<meta property="og:type" content="website">
	<meta property="og:title" content="Blackparadox - Fotografía">
	<meta property="og:description" content="Expertos en fotografía, retratamos los momentos que siempre quieres conservar contigo, con más de 15 años de experiencia en crear recuerdos inolvidables">
	<meta property="og:image" content="https://www.blackparadox.com/images/logo_blackparadox.svg">
	
	<!-- Bootstrap 4 CDN -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css" integrity="sha384-PsH8R72JQ3SOdhVi3uxftmaW6Vc51MKb0q5P2rRUpPvrszuE4W1povHYgTpBfshb" crossorigin="anonymous">

	<!-- Estilos -->
	<link rel="stylesheet" href="css/main.css">

	<!-- Favicon -->
	<link rel="shortcut icon" href="favicon/favicon.ico?v=2" type="image/x-icon">
	<link rel="icon" href="favicon/favicon.ico?v=2" type="image/x-icon">


	
</head>
<body>
	
	<!-- navigation -->
	<nav id="nav">
		<div class="container-fluid">
			<div class="row">
				<!-- Our logo -->
				<div class="col-xl-2">
					<a href="http://www.blackparadox.com" class="logo">
						<img src="images/logo.svg" alt="Logo Blackparadox">
					</a>
				</div>
				<!-- Our navigation links -->
				<div class="col-xl-10">
					<ul>
						<li class="link-active"><a href="index.html">Home</a></li>
						<li><a href="index.html#company">Company</a></li>
						<li><a href="portfolio.html">Portfolio</a></li>
						<li><a href="contact.html">Contact</a></li>
					</ul>
				</div>
			</div>
		</div>		
	</nav>
	<!-- ends navigation -->

	<!-- slider -->
	<!-- ends slider -->

	<!-- company section -->
	<!-- ends -->

	<!-- services section -->
	<!-- ends -->

	<!-- footer -->
	<!-- ends footer -->









	<!-- Bootstrap 4 JS CDN -->
	<script src="https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js" integrity="sha384-vFJXuSJphROIrBnz7yo7oB41mKfc8JzQZiCq4NCceLEaO4IHwicKwpJf9c9IpFgh" crossorigin="anonymous"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/js/bootstrap.min.js" integrity="sha384-alpBpkh1PFOepccYVYDB4do5UnbKysX5WZXm3XxPqe5iKTfUKjNkCk9SaVuEZflJ" crossorigin="anonymous"></script>
	<script src="js/slippry.min.js"></script>
	
</body>
</html>
```

project_folder > `portfolio.html`

```html
<h1>You are in Portfolio Section</h1>
<a href="index.html">Return</a>
```

project_folder > `contact.html`

```html
<h1>You are in Contact Section</h1>
<a href="index.html">Return</a>
```

### Adding Styles to the NavBar - Part 1

project_folder > css > `main.sass`

```sass
// Blackparadox
// Styles 2017
// Version: 1.0.1

// Color Variables
$base: #060a0f
$sec: #494949
$outline: #ff6600
$text: transparentize($sec, .5)

// General Styles
a 
	margin: 0px
	padding: 0px
	@extend .tSlow;
	&:hover
		color: $outline
h1, h2, h3, h4, h5, h6
	color: $base
p 
	color: $sec

.tSlow
	-webkit-transition: all 0.5s ease-in-out
	-o-transition: all 0.5s ease-in-out
	transition: all 0.5s ease-in-out
.pad_200
	padding: 200px 0px
.center
	text-align: center
	margin: 0px auto
.main-title
	font-size: 60px
	font-weight: bold
	color: $base


// Styles of Inputs, Textarea, Buttons

// Styles of NavBar
nav
	width: 100%
	background-color: lighten(red, 40)
	padding: 10px 0px
	position: fixed
	border-bottom: 1px solid transparent
	z-index: 100
	@extend .tSlow;
	.logo
		img
			width: 100%
			@extend .tSlow;
	ul 
		margin: 0px 
		margin-top: 8px
		padding: 0px 
		text-align: right 
		@extend .tSlow;
		.link-active
			a 
				color: $base !important
				&:after 
					width: 100%
					background-color: $base 
					@extend .tSlow;
		li 
			display: inline-block
			padding: 0px 10px
			a 
				position: relative 
				text-decoration: none
				font-size: 16px
				color: $text 
				@extend .tSlow;
				&:before 
					content: ''
					position: absolute
					width: 100%
					background-color: transparent
					height: 1px
					@extend .tSlow;
				&:after 
					content: ''
					position: absolute 
					top: 100%
					left: 0px 
					width: 100%
					background-color: transparent 
					height: 1px 
					@extend .tSlow;
				&:hover
					background-color: purple
					text-decoration: none 
					color: $base
					&:before 
						width: 0%
						background-color: $base 
					&:after
						width: 100%
						background-color: $base
```

project_folder > `index.html`

```html

```


## Portfolio Section

## Contact Section

## Corrections, Fixes & Conclusions
