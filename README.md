css.js
======

A lightweight, battle tested, fast, css parser in JavaScript


Demo
======

Check it out [plunker demo]

[plunker demo]: http://embed.plnkr.co/qMRJpJ92BHNrJuCnbRFB/preview

Development
======

Following commands will prepare development enviroment by installing dependencies:

```
	npm install
	bower install
```

And to execute unit tests and produce css.min.js, execute

```
	grunt
```

How To Use
======


Simply parse css string, and log the output

```
	<script type="text/javascript" src="css.min.js"></script>
	<script type="text/javascript">
		var cssString = ' .someSelector { margin:40px 10px; padding:5px}';
		//initialize parser object
		var parser = new cssjs();
		//parse css string
		var parsed = parser.parseCSS(cssString);

		console.log(parsed);
	</script>
```



