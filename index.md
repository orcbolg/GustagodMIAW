<html>
  <body>
 <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHu000001AFbk',
				'MIAWWEB',
				'https://playcorpgod-dev-ed.develop.my.site.com/ESWMIAWWEB1695702372980',
				{
					scrt2URL: 'https://playcorpgod-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://playcorpgod-dev-ed.develop.my.site.com/ESWMIAWWEB1695702372980/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
