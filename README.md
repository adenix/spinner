# Spinner CSS

### Description

Spinner CSS is a loading spinner that is generated entirely in css.

### Example

<div spinner>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</div>

### How to use with JavaScript

1) Include <code>spinner.css</code> near the bottom of head in your html
```html
<head>
  ...
  <link href="spinner.css" rel="stylesheet" />
</head>
```

2) Include <code>spinner.js</code> near the bottom of the body in your html
```html
<body>
  ...
  <script src="spinner.js"></script>
</body>
```

3) Place the <code>spinner</code> attribute on the element you'd like to contain the spinner. (make sure it is a block element)
```html
<div spinner></div>
```

### How to use without JavaScript

1) Include <code>spinner.css</code> near the bottom of head in your html.
```html
<head>
  ...
  <link href="spinner.css" rel="stylesheet" />
</head>
```

2) Place the <code>spinner</code> attribute on the element you'd like to contain the spinner. (make sure it is a block element)
```html
<div spinner></div>
```

3) Put 12 <code>div</code> elements in the element that you added the <code>spinner</code> attribute to in the last step.
```html
<div spinner>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</div>
```

<style>
@-webkit-keyframes spinner-pulse {
    0% {
        opacity: 1;
    }
    100% {
        opacity: 0;
    }
}
@keyframes spinner-pulse {
    0% {
        opacity: 1;
    }
    100% {
        opacity: 0;
    }
}
[spinner] {
    position: relative;
    background: none;
    width: 200px;
    height: 200px;
    transform: scale(1);
}
[spinner] > div {
    -webkit-animation: spinner-pulse 1s linear infinite;
    -moz-animation: spinner-pulse 1s linear infinite;
    -ms-animation: spinner-pulse 1s linear infinite;
    -o-animation: spinner-pulse 1s linear infinite;
    animation: spinner-pulse 1s linear infinite;
    width: 14px;
    height: 40px;
    background: #3d82c4;
    border-radius: 10px;
    position: absolute;
    left: 45%;
    top: 40%;
}
[spinner] > div:nth-of-type(1) {
    opacity: 0.92308;
    -webkit-animation-delay: -0.5s;
    -moz-animation-delay: -0.5s;
    -ms-animation-delay: -0.5s;
    -o-animation-delay: -0.5s;
    animation-delay: -0.5s;
    -webkit-transform: rotate(0deg) translate(0, -60px);
    -moz-transform: rotate(0deg) translate(0, -60px);
    -ms-transform: rotate(0deg) translate(0, -60px);
    -o-transform: rotate(0deg) translate(0, -60px);
    transform: rotate(0deg) translate(0, -60px);
}
[spinner] > div:nth-of-type(2) {
    opacity: 0.84615;
    -webkit-animation-delay: -0.41667s;
    -moz-animation-delay: -0.41667s;
    -ms-animation-delay: -0.41667s;
    -o-animation-delay: -0.41667s;
    animation-delay: -0.41667s;
    -webkit-transform: rotate(30deg) translate(0, -60px);
    -moz-transform: rotate(30deg) translate(0, -60px);
    -ms-transform: rotate(30deg) translate(0, -60px);
    -o-transform: rotate(30deg) translate(0, -60px);
    transform: rotate(30deg) translate(0, -60px);
}
[spinner] > div:nth-of-type(3) {
    opacity: 0.76923;
    -webkit-animation-delay: -0.33333s;
    -moz-animation-delay: -0.33333s;
    -ms-animation-delay: -0.33333s;
    -o-animation-delay: -0.33333s;
    animation-delay: -0.33333s;
    -webkit-transform: rotate(60deg) translate(0, -60px);
    -moz-transform: rotate(60deg) translate(0, -60px);
    -ms-transform: rotate(60deg) translate(0, -60px);
    -o-transform: rotate(60deg) translate(0, -60px);
    transform: rotate(60deg) translate(0, -60px);
}
[spinner] > div:nth-of-type(4) {
    opacity: 0.69231;
    -webkit-animation-delay: -0.25s;
    -moz-animation-delay: -0.25s;
    -ms-animation-delay: -0.25s;
    -o-animation-delay: -0.25s;
    animation-delay: -0.25s;
    -webkit-transform: rotate(90deg) translate(0, -60px);
    -moz-transform: rotate(90deg) translate(0, -60px);
    -ms-transform: rotate(90deg) translate(0, -60px);
    -o-transform: rotate(90deg) translate(0, -60px);
    transform: rotate(90deg) translate(0, -60px);
}
[spinner] > div:nth-of-type(5) {
    opacity: 0.61538;
    -webkit-animation-delay: -0.16667s;
    -moz-animation-delay: -0.16667s;
    -ms-animation-delay: -0.16667s;
    -o-animation-delay: -0.16667s;
    animation-delay: -0.16667s;
    -webkit-transform: rotate(120deg) translate(0, -60px);
    -moz-transform: rotate(120deg) translate(0, -60px);
    -ms-transform: rotate(120deg) translate(0, -60px);
    -o-transform: rotate(120deg) translate(0, -60px);
    transform: rotate(120deg) translate(0, -60px);
}
[spinner] > div:nth-of-type(6) {
    opacity: 0.53846;
    -webkit-animation-delay: -0.08333s;
    -moz-animation-delay: -0.08333s;
    -ms-animation-delay: -0.08333s;
    -o-animation-delay: -0.08333s;
    animation-delay: -0.08333s;
    -webkit-transform: rotate(150deg) translate(0, -60px);
    -moz-transform: rotate(150deg) translate(0, -60px);
    -ms-transform: rotate(150deg) translate(0, -60px);
    -o-transform: rotate(150deg) translate(0, -60px);
    transform: rotate(150deg) translate(0, -60px);
}
[spinner] > div:nth-of-type(7) {
    opacity: 0.46154;
    -webkit-animation-delay: 0s;
    -moz-animation-delay: 0s;
    -ms-animation-delay: 0s;
    -o-animation-delay: 0s;
    animation-delay: 0s;
    -webkit-transform: rotate(180deg) translate(0, -60px);
    -moz-transform: rotate(180deg) translate(0, -60px);
    -ms-transform: rotate(180deg) translate(0, -60px);
    -o-transform: rotate(180deg) translate(0, -60px);
    transform: rotate(180deg) translate(0, -60px);
}
[spinner] > div:nth-of-type(8) {
    opacity: 0.38462;
    -webkit-animation-delay: 0.08333s;
    -moz-animation-delay: 0.08333s;
    -ms-animation-delay: 0.08333s;
    -o-animation-delay: 0.08333s;
    animation-delay: 0.08333s;
    -webkit-transform: rotate(210deg) translate(0, -60px);
    -moz-transform: rotate(210deg) translate(0, -60px);
    -ms-transform: rotate(210deg) translate(0, -60px);
    -o-transform: rotate(210deg) translate(0, -60px);
    transform: rotate(210deg) translate(0, -60px);
}
[spinner] > div:nth-of-type(9) {
    opacity: 0.30769;
    -webkit-animation-delay: 0.16667s;
    -moz-animation-delay: 0.16667s;
    -ms-animation-delay: 0.16667s;
    -o-animation-delay: 0.16667s;
    animation-delay: 0.16667s;
    -webkit-transform: rotate(240deg) translate(0, -60px);
    -moz-transform: rotate(240deg) translate(0, -60px);
    -ms-transform: rotate(240deg) translate(0, -60px);
    -o-transform: rotate(240deg) translate(0, -60px);
    transform: rotate(240deg) translate(0, -60px);
}
[spinner] > div:nth-of-type(10) {
    opacity: 0.23077;
    -webkit-animation-delay: 0.25s;
    -moz-animation-delay: 0.25s;
    -ms-animation-delay: 0.25s;
    -o-animation-delay: 0.25s;
    animation-delay: 0.25s;
    -webkit-transform: rotate(270deg) translate(0, -60px);
    -moz-transform: rotate(270deg) translate(0, -60px);
    -ms-transform: rotate(270deg) translate(0, -60px);
    -o-transform: rotate(270deg) translate(0, -60px);
    transform: rotate(270deg) translate(0, -60px);
}
[spinner] > div:nth-of-type(11) {
    opacity: 0.15385;
    -webkit-animation-delay: 0.33333s;
    -moz-animation-delay: 0.33333s;
    -ms-animation-delay: 0.33333s;
    -o-animation-delay: 0.33333s;
    animation-delay: 0.33333s;
    -webkit-transform: rotate(300deg) translate(0, -60px);
    -moz-transform: rotate(300deg) translate(0, -60px);
    -ms-transform: rotate(300deg) translate(0, -60px);
    -o-transform: rotate(300deg) translate(0, -60px);
    transform: rotate(300deg) translate(0, -60px);
}
[spinner] > div:nth-of-type(12) {
    opacity: 0.07692;
    -webkit-animation-delay: 0.41667s;
    -moz-animation-delay: 0.41667s;
    -ms-animation-delay: 0.41667s;
    -o-animation-delay: 0.41667s;
    animation-delay: 0.41667s;
    -webkit-transform: rotate(330deg) translate(0, -60px);
    -moz-transform: rotate(330deg) translate(0, -60px);
    -ms-transform: rotate(330deg) translate(0, -60px);
    -o-transform: rotate(330deg) translate(0, -60px);
    transform: rotate(330deg) translate(0, -60px);
}
</style>