# wordcampus-2015-js-example
A simple web page that makes use of data from a WordPress JSON REST API

## Instructions

This web page is used as an example for a presentation at WordCamp US 2015, [“Decoupled Development with WordPress JSON APIs”](https://2015.us.wordcamp.org/session/decoupled-development-with-wordpress-json-apis/)

It is the client-side counterpart to the WordPress JSON REST API site that can be built using the [wordcampus-2015-rest-api](https://github.com/dirtystylus/wordcampus-2015-rest-api) repo.

To use this example:

* Sign up for a free [Mapbox developer account](https://www.mapbox.com)
* Create an application on Mapbox. Get your App ID and your Access Token
* In the inline script, you will see three stubs for your data:
  * [YOUR ARTWORK ENDPOINT GOES HERE] - replace this (including the brackets) with the URL for your WordPress JSON REST API Artwork endpoint. This should be something like: http://wordcampus2015.local/wp-json/wp/v2/artwork
  * [YOUR MAPBOX APP ID GOES HERE] - replace this with your Mapbox App Id
  * [YOUR MAPBOX ACCESS TOKEN GOES HERE] - replace this with your Mapbox Access Token