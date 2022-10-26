### HTML
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>

<script>
function fizzbuzz() {
var display = document.getElementById('display');
var displayHTML = "";
for (i = 0; i < 100; i++) {
displayHTML += "<p>" + i + "</p>";
}
display.innerHTML = displayHTML;
