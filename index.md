<html>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D8Z000000sp44',
				'MIAW_GitHub_Omni_Flow_Pre_Chat_LWC',
				'https://infallibletechiemiaw.my.site.com/ESWMIAWGitHubOmniFlow1701951779465',
				{
					scrt2URL: 'https://infallibletechiemiaw.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://infallibletechiemiaw.my.site.com/ESWMIAWGitHubOmniFlow1701951779465/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</html>
