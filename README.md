# HoverSum
A tool for adding currency numbers on a webpage together, simply by hovering over them.

After referencing the hoversum.js script, simply create a hoverSum object, and then the tool will begin.

```javascript
var hs = new HoverSum();
```

Hover over currency numbers on the page to see them add up, into a hovering sum value. Click on the hoversum value to reset it to zero.

Negative numbers will be represented ad inside parentheses: ($1,234,567.89)

Numbers hovered over in this format or in the standard negative format -1,234,567.89 will be recorded as negative.
