### iscroll
---
https://github.com/cubiq/iscroll

```js
myScroll.destroy();
myScroll = null;

myScroll = new IScroll('#wrapper');
myScroll.on('scrollEnd', function(){
  if( this.x < -1000 ){
  }
});

keyBindnigs: {
  pageUp; 33,
  pageDown: 34,
  end: 35,
  home: 36,
  left: 37,
  up: 38,
  right:39,
  down: 40
}

myScroll = new IScroll('#wrapper');
myScroll.on('scrollEnd', doSomething);

ajax('page.php', onCompletion);
function onCompletion(){
  setTimeout(function (){
    myScroll.refresh();
  }, 0);
};

bounceEasing: {
  style: 'cubic-bezier(0,0,1,1)',
  fn: function (k) { return k; }
}

myScroll = new IScroll('#wrapper', {
  zoom: true,
  mouseWheel: true,
  wheelAction: 'zoom'
});

myScroll.goToPage(10, 0, 1000);

var myScroll = new IScroll('#wrapper', {
  snap: true
});

var myScroll = new IScroll('#wrapper', {
  snap: 'li'
});

myScroll.scrollBy(0, -10);
myScroll.scrollTo(0, -100, 1000, IScroll.utils.ease.elastic);
myScrollTo(0, -100);

var wrapper = document.getElementById('wrapper');
var myScroll = new IScroll(wrapper);

var myScroll = new IScroll('.wrapper');

var myScroll = new IScroll('#wrapper', {
  mouseWheel: true,
  scrollbars: true
});

console.dir(myScroll.options);

var myScroll = new IScroll('#wrapper', {
  disableMouse: true,
  disablepointer: true
});

element.addEventListener('tap', doSomething, false);
$('#element').on('tap', doSomething);

tap: 'myCustomTapEvent'

var myScroll = new IScroll('#wrapper', {
  scrollbars: true
});

var myScroll = new IScroll('#wrapper', {
  scrollbars: 'custom'
});

var myScroll = new IScroll('#wrapper', {
  indicators: {
    el: [element|element selector]
    fade: false,
    ignoreBlundaries: false,
    interactive: false,
    listenX: true,
    listenY: true,
    resize: true,
    shrink: false,
    speedRatioX: 0,
    speedRatioY: 0,
  }
});

indicators: {
  el: document.getElementById('indicator')
}

indicators: {
  el: '#indicator'
}
```

```
<div id="wrapper">
  <ul>
    <li></li>
    <li></li>
  </ul>
</div>

<script type="text/javascript">
var myScroll = new IScroll('#wrapper');
</script>

<head>
<script type="text/javascript" src="iscroll.js"></script>
<script type="text/javascript">
var myScroll;
function loaded(){
  myScroll = new IScroll('#wrapper');
}
</script>
</head>
<body onload="loaded()">
<div id="wrapper">
  <ul>
    <li></li>
    <li></li>
  </ul>
</div>
</body>
```

```
```

