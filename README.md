# json-utils

## About 

A place for utilities to help working with JSON in Java
Currently only support org.json.JSONObject (& JSONArray)

## Maven deploy 

Some notes to myself for manually deploying to [bintray](https://bintray.com/ianmorgan/commons)

* Update version in build.gradle and build locally 
* local copy of 'gradle.properties' with the 'bintray_api_key'  
* deploy with '.\gradlew bintrayUpload'
* Update build.gradle manually to next snapshot version & commit 

