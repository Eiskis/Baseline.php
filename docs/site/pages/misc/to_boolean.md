
# to_boolean

**Convert an object or variable into boolean.** [View source](https://github.com/Eiskis/Baseline-PHP/blob/master/source/misc/to_boolean.php)

	function to_boolean ($value)

...



## Examples

### Trues

	to_boolean(120);
	to_boolean('true');
	to_boolean(array(1, 2, 3));

### Falses

	to_boolean(0);
	to_boolean(-1);
	to_boolean(false);
	to_boolean(null);
	to_boolean(array());
	to_boolean('');
	to_boolean('false');
	to_boolean('null');
