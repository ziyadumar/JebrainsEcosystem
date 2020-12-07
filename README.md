## JebrainsEcosystem
Few services from Jetbrains ecosystem are compiled to run together in a dockerized way. All images for the services are taken from the dockerhub, including a postgres instance for database service for the teamcity server.
Also multiple teamcity build agents can be appended as you wish.

The nginx conf shows a way to run each service in dedicated subdomain, for this you need wildcard configuration. It's also best to have HTTPS for smooth setup and your safety certification ofcourse.
Upsource and Youtrack are connected to the Hub.
Teamcity has one build agent in the docker-compose configuration. 

If you are this far, you must know the rest.

GodSpeed!
