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
#test video
<iframe width="560" height="315" src="https://www.youtube.com/embed/6uPKcJJCZmw?si=eDUOl1GI7N56wPjZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
