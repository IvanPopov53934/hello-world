<!DOCTYPE html>
<html>
<head>
<script src="http://code.jquery.com/jquery-latest.js">
</script>

<button id="but1">Скрыть нечетный элементы.</button>

<button id="but2">Показать нечетный элементы.</button>

<button id="but3">Скрыть четный элементы.</button>

<button id="but4">Показать четный элементы.</button>

<button id="but5">Скрыть список.</button>

<button id="but6">Показать список.</button>

<button id="but7">Скрыть текст по центру.</button>

<button id="but8">Показать текст по центру.</button>

<script>
$(document).ready(function ()

{$("#but1").click(function ()
{$( '.MsNormal').hide();
});
$("#but2").click(function()
{$('.MsNormal').show();
});});

$(document).ready(function ()

{$("#but3").click(function ()
{$("tr").hide();});
$("#but4").click(function()
{$("tr").show();
});});

$(document).ready(function ()

{$("#but5").click(function ()
{$('[href]').hide();
});
$("#but6").click(function()
{$('[href]').show();
});});

$(document).ready(function ()

{$("#but7").click(function ()
{$('[align="center"]').hide();
});
$("#but8").click(function()
{$('[align="center"]').show();
});});


</script>

</head>

<body>
<h2>This is a heading 2</h2>

<p>This is a paragraph.</p>

<p class="MsNormal">Нечетный элемент.</p>

<table><td><td><p>Четный элемент.</p></td></tr></table>

<p class="MsNormal">Нечетный элемент.</p>

<table><td><td><p>Четный элемент.</p></td></tr></table>

<a name="list">список</a>
<ul>
<li><a href="http://google.com">http://google.com</a></li>
<li><a href="http://nodejs.org">http://nodejs.org</a></li>
</ul>

<p align="center">235235235234123текст по центру5325235235235</p>

</body>

</html>
