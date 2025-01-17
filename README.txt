Install:
	- copy json file and import to nodered
	- configure inject node:
			- traktList: your list to query in trakt (where you save the series, make it public)
			- traktApiKey: create here, https://trakt.tv/oauth/applications/new
			- traktUrl: https://api.trakt.tv
			- traktUser: your trakt user name, find it at settings > account
			- sonarrApiKey: find it at sonarr > settings > general , scroll to security
			- sonarrUrl: your sonar local url
			- sonnarAddSeriesConfig: config to download (modify the quality profile id for yours , you find your profile ids at http://<url>:<port>/api/v3/qualityprofile?apikey=<your api key>)
