# _*CSS-reset*_
## This is the css reset I use. It's basically Josh W Comeau css-reset but I added  some extra things.
*, *::before, *::after {
	font-family: 'Roboto Slab', serif;
	box-sizing: border-box;
	-webkit-tap-highlight-color: transparent;
	margin: 0;
}

*:focus {
	-webkit-tap-highlight-color: transparent;
}
textarea:focus, input:focus {
	outline: none;
}
span {
	user-select: none;
}
html, body {
	background: black;
	height: 100%;
}
body {
	background: black;
	line-height: 1.5;
	-webkit-font-smoothing: antialiased;
}
img, picture, video, canvas, svg {
	display: block;
	max-width: 100%;
}
input, button, textarea, select {
	font: inherit;
}
p, h1, h2, h3, h4, h5, h6 {
	overflow-wrap: break-word;
}
#root, #__next {
	isolation: isolate;
}
