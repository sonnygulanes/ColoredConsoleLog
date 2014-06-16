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
				<script>var Log = Object.create(Log.prototype);
				//Log.disableInfo();
				//Log.style.value = ['color:WHITE; background:RED;','color:#ff1b50; background:WHITE; font-style: italic;','color:BLUE; background:WHITE; font-weight:bold;','color:GREEN; background:WHITE; font-weight:bold;','color:BLACK; background:WHITE; font-weight:bold;']
				//Log.style.value[0] = 'color:WHITE; background:YELLOW; font-style:underline; font-weight:bold;';
				
				/*
				Log.style.value[0] - error
				Log.style.value[1] - warning
				Log.style.value[2]  - debug
				Log.style.value[3]  - info
				Log.style.value[4]  - verbose
				*/
				</script>
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
