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

## Home & Company Section

## Portfolio Section

## Contact Section

## Corrections, Fixes & Conclusions
