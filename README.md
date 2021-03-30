# Edmonlytica - Browser Tag

Edmonlytica is a proof of concept for making your own digital analytics stream using GTM Server Side and BigQuery.  See the blog post for details:
https://code.markedmondson.me/edmondlytica/

## Dependencies

This is the browser tag to be imported into GTM Browser Side.  It works in conjunction with the [Edmonlytica GTM Server Side Client](https://github.com/MarkEdmondson1234/edmonlytica-server-side-client) and the [Edmonlytica GTM Server Side Tag](https://github.com/MarkEdmondson1234/edmonlytica-server-side-tag), which need to be installed as well to work.

## Functionality

This gathers data from your GTM dataLayer and sends it to the /edmonlytica ednpoint, which is intended to be your GTM Server Side client.
