# apps_repository
Test for an application repository based on github.


Structure:
===========
apps_repository
	applications
		{myAppFolder}
			{myAppfiles}
			app.json
		applications.json
	web
		metadata_generator.html (app.json generator)
		{Instructions WebSite}
	more
		{more_Appfiles}
	index.html
	LICENCE
	README.md

=================
The App fetch the list of folder to scan (applications.json)
and scan the app.json only those for the current page (offset and perpage parameter)
