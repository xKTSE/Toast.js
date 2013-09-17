Toast.js - Android-like Notifications for Web
=============================================
An easy to use and quick toast-like notification for your web applications.

## Usage
```js
var options = {
    			text: "XKTSE",	// String
				duration: 10000	// Integer
			};

var toast = new Toast(options);
// Toast will immediately appear near the bottom of the page upon creation
```

## Options
There are 2 options that you can use when creating new toasts.

<table>
	<tr>
		<td><code>text</code> - REQUIRED - The text message that the end user will see</td>
	</tr>
	<tr>
		<td><code>duration</code> - OPTIONAL - The duration of the toast (in milliseconds.) By default, if the duration is not set, the toast duration is 2 seconds.</td>
	</tr>
</table>

## Open Source License
[MIT](http://www.opensource.org/licenses/mit-license.php)
