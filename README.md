jqEasyCharCounterX is the same version of jqEasyCharCounter. The only difference isthe "Characters" text has been removed.
All credits to the jqeasy.
http://www.jqeasy.com/jquery-character-counter/

Uses:
Character limit for ecommerce product personalisation like PrestaShop, Magento 2 and BigCommerce. You need to customize the script according to the css ID and Class in your website template.

Add the scripts in the header or footer before jquery.
<script src="https://marlanuengo.github.io/jqEasyCharCounterX/jquery.jqEasyCharCounter.min.js"></script>
<script>
  $(document).ready(function () {
    $('div .jqEasyCounterMsg').show();
    $('#inputchar').jqEasyCounter({
      'maxChars': 5,
      'maxCharsWarning': 5
    });			
  });
</script>

Example:
<html>
	<head>
		<script src="https://code.jquery.com/jquery-3.1.1.min.js"></script>
		<script src="https://marlanuengo.github.io/jqEasyCharCounterX/jquery.jqEasyCharCounter.min.js"></script>
	</head>
	<body>
		<div class="jqEasyCounter">
			<input id="inputchar" name="inputchar" type="text"/>
		</div>
		<script>
			$(document).ready(function () {
				$('div .jqEasyCounterMsg').show();
				$('#inputchar').jqEasyCounter({
					'maxChars': 5,
					'maxCharsWarning': 5
				});			
			});
		</script>
	</body>
</html>

For help contact me.
