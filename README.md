# JavaScript-to-detect-WebPage
JavaScript to detect whether page is load on Mobile or Desktop

```
<!DOCTYPE html>
<html>
<head>
	<title>Mobile Test</title>
</head>
<body>

	<p id="text"></p>

	<script type="text/javascript">
		var isMobile = /iPhone|iPad|iPod|Android/i.test(navigator.userAgent);
		var element = document.getElementById('text');
		if (isMobile) {
  			element.innerHTML = "You are using Mobile";
		} else {
			element.innerHTML = "You are using Desktop";
		}
	</script>
</body>
</html>

```
# Live Demo:
<iframe width="560" height="315" src="http://nazmulalamshuvo.42web.io/projects/JavaScript-to-detect-WebPage/" title="JavaScript-to-detect-WebPage" ></iframe>
