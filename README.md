# bootstrap-btn-push
Bootstrap 3.3.7 / Background Push-Slide Effect Button

Examples: https://jsfiddle.net/Nyanyame/ggjxhyqw/3/

## Default Class
**Required**

WHITE TEXT + BLACK BACKGROUND: `<a class="btn btn-push btn-push-white" href="#">Button</a>`

BLACK TEXT + WHITE BACKGROUND: `<a class="btn btn-push btn-push-black" href="#">Button</a>`

## Rotation
**Default: Left to Right**

Left to Right: `<a class="btn btn-push btn-push-white btn-push-left" href="#">Left to Right</a>`

Right to Left: `<a class="btn btn-push btn-push-white btn-push-right" href="#">Right to Left</a>`

Top to Bottom: `<a class="btn btn-push btn-push-white btn-push-top" href="#">Top to Bottom</a>`

Bottom to Top: `<a class="btn btn-push btn-push-white btn-push-bottom" href="#">Bottom to Top</a>`

## Size
**Default: Normal** (No include btn-[size] class)

Extra Small: `<a class="btn btn-push btn-push-black btn-xs" href="#">X-Small Button</a>`

Small: `<a class="btn btn-push btn-push-black btn-sm" href="#">Small Button</a>`

Normal: `<a class="btn btn-push btn-push-black" href="#">Default Button</a>`

Large: `<a class="btn btn-push btn-push-black btn-lg" href="#">Large Button</a>`

## Custom Color
**You can make background-image here http://png-pixel.com/**

<pre>.btn.btn-push.btn-push-[color_name] {
	background-image: url([input data:image-url]);
	background-position: top left;
	background-size: 0% 100%;
	-webkit-transition: ease .5s all;
	transition: ease .5s all;
	color: [text_color];
	border: 1px solid [color_hex or rgba];
}</pre>
