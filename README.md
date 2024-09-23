# keycloak-themes
Custom keycloak themes for Oslo Origo

## How to use
* Add a new theme in custom-themes/themes directory. Follow the same pattern as origo-booking-admin.
* Include the theme in custom-themes/META-INF/keycloak-themes.json
* Update the jar file with ./update-jar.script
* Make a new release in github (git tag -a vx.x.x -m "Release x.x.x")
* Upload the jar file to github releases for the tag you just made.
* Ping Eivind to make a Kompass ticket to update the theme in Keycloak prod.
