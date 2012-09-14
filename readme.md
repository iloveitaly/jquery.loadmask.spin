jQuery LoadMask Spinner Plugin
==============================

Based off of the [loadmask jQuery plugin](http://code.google.com/p/jquery-loadmask/) and inspired by the [MooTools Spinner class](http://mootools.net/docs/more/Interface/Spinner). Adds a customizable overlay to the element being masked and adds  a spinner graphic along with a label on top of the 

Uses [spin.js](http://fgnass.github.com/spin.js/) for spinner generation. Note that spin.js is not included by default, you'll have to pull that into your project for yourself.

Customization & Usage
---------------------

```
$('#element').mask();
$('#element').mask({
	spinner: { lines: 10, length: 5, width: 3, radius: 10},
	delay: 1000
});
$('#element').unmask();
```

Checkout the options for customization options.


Authors
-------
* Sergiy Kovalchuk
* Michael Bianco (@iloveitaly)

License
--------
Dual licensed under the MIT (<http://www.opensource.org/licenses/mit-license.php>) and GPL (<http://www.opensource.org/licenses/gpl-license.php>) licenses.