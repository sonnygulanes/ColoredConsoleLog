ColoredConsoleLog
=================

Colored Javascript Console Log

Use: Add Log.min.js to your website and create a variable named Log "var Log = Object.create(Log.prototype);"

		<!doctype html>
		<html lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml">
			<head>
				<meta content="text/html; charset=utf-8" http-equiv="Content-Type">
				<title>Colored Console Log</title>

				<script src="Log.min.js" type="text/javascript"></script>
				<script>var Log = Object.create(Log.prototype);</script>
			</head>
			<body>
		<script>

		Log.e("error");
		Log.d("debug");
		Log.w("warning");
		Log.v("verbose");
		Log.i("info");
		</script>
			</body>
		</html>
