writeCode

- Create a layout according to the design shown below.

![Backgrounds and gradient Assignment level 1](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/background-and-gradients/ex-1.png)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

- Chose your own image.
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="background.css">
</head>
<body>
    <div class="container">
    <h1>Background and Gradients</h1>
    <div class="flex">
    <div class="box"></div>
    <div class="box box1"></div>
    <div class="box box2"></div>
    </div>
    </div>

    <div class="container2">
        <div class=big-box >
            
        </div>
    </div>

</body>
</html>





html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}

/* customised code  */
.container{
    height: 500px;
    width: 100%;
    background-image: url("/merging-background/milky-way-2695569__480.jpeg");
    background-size: 100%;
}
h1{
    text-align: center;
    color: white;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 30px;
    padding-top: 20px;
}
.box{
    height: 200px;
    width: 200px;
    background-color:  rgb(245, 55, 55);
    border-radius: 5px;
    margin: 96px 18px 4px 173px;
}

.box1{
    background-image: linear-gradient(to right, rgb(44, 41, 41),rgb(245, 55, 55));
}
.flex{
    display: flex;

}
.box2{
    background-image: radial-gradient(rgb(245, 55, 55), rgb(44, 41, 41));
}


.container2{
    height: 1000px;
    width: 100%;  
    background-image: url("/merging-background/pngtree-modern-double-color-futuristic-neon-background-image_351866.jpeg");
    background-size: 100% 500px ;
}
.big-box{
    height: 200px;
    width: 200px;
    background:url("/merging-background/photo-1514565131-fce0801e5785.jpeg") 300px 300px;
    border-radius: 5px;
    padding: 96px 18px 4px 173px;
    margin-left: 36%;
}

