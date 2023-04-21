# &lt;!-- &gt;

Comments do not show up in the browser. They are used to explain complex parts of your code.

```html
<!--This is a comment. Comments are not displayed in the browser-->
```

Comments can also be used to "hide" scripts from browsers so they are not shown as plain text. Use a double slash on the last comment bracket to prevent javascript from executing the code.

``` html
<script type="text/javascript">
<!--
function displayMsg() {
  alert("Hello World!")
}
//-->
</script> 
```
