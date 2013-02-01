# jQuery Currency Format Plugin

## jQuery plugin to changing numbers to currency format



### Usage

```
$(el).dollar([number][, options]);
```

**number** : if you want to replace what's inside your selected node - leave blank if you want to manipulate what's in the node

**options** : Object containing settings for commas and currency symbol. (default to true and "$")

```
{ comma : [true/false], symbol : [true/false/€/£] }
```

### Example

```
var cost = $('<span>')

$cost.dollar((300.234 + 34.234324),{ commas: true, symbol: "£" });

cost.appendTo("#total");

```

```<span>​£334.47​</span>​``` is appended to ```<div id="total"> </div>```.

