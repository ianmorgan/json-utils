# json-utils

## About 

A place for utilities to help working with JSON in Java
Currently only support org.json.JSONObject (& JSONArray)

## Maven deploy 

Some notes to myself for manually deploying to bintray.

* Update version in build.gradle and build locally 
* Create matching version in bintray through the UI
* Manually upload the jar in build\libs through the UI
* Rename the pom file in build\poms to 'json-utils-<version>.pom'
* Upload through the bintray UI and ignore the warning
* Update build.gradle manually to next snapshot version & commit 

