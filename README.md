# Ayu Mirage for DuckDuckGo
Unofficial Ayu Mirage color theme for the DuckDuckGo search engine  
Inspired by <https://github.com/ayu-theme>

## Applying the theme 

1. Visit <https://duckduckgo.com>.
2. Right click and select the “Inspect” button.
3. Select the “Console” tab.
4. If you are using Firefox, type `allow pasting`.
5. Paste the following script and press enter:

	```js
	const theme = [
	'21=242936', '7=1F2430', '8=CBCCC6', '9=5CCFE6', 'aa=5CCfE6',
	'ae=1F2430', 'j=1A1F29', 'x=A6CC70',
	];
	
	for (const item of theme) {
		document.cookie = `${item}; max-age=126144000; samesite=lax; secure`;
	}
	```

6. Reload the page.
