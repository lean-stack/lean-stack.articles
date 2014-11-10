
## CSS-Class hinzufügen

## jQuery
$elt.addClass('klasse')

## Vanilla JS
var classList = elt.className;
var classes = classList.split(' ');
if( classes.indexOf('klasse') === -1) {
	classes.push('klasse')
}
elt.className = classes.join(' ');

