<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D2w000006VRGJ',
				'MessagingWebPOC',
				'https://curious-badger-qi13n6-dev-ed.my.site.com/ESWMessagingWebPOC1724858927327',
				{
					scrt2URL: 'https://curious-badger-qi13n6-dev-ed.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://curious-badger-qi13n6-dev-ed.my.site.com/ESWMessagingWebPOC1724858927327/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
