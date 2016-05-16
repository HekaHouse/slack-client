# slack-client

`<slack-client>` a collection  of elements representing a client for Slack Realtime Messaging API

[API Docs and Demo](https://heka-house-slack-client-demo.firebaseapp.com/)

[Source](http://github.com/hekahouse/slack-client/)

The label is set to the path of the value.

## Install

    bower install --save HekaHouse/slack-client

## Example
    <slack-client
      route="ACTIVE-ROUTE"
      path="DISPLAY-ROUTE"
      team="SLACK-TEAM"
      oauth-callback="OAUTH-CALLBACK-URL"
      client-id-path="PATH-TO-ID-ON-FIREBASE"
      client-secret-path="PATH-TO-SECRET-ON-FIREBASE"></slack-client>

In the above example replace YOUR-FIREBASE, COLLECTION, ITEM and LEAF-PATH with appropriate values from your Firebase.

LEAVES are a collection of the full paths to Firebase values ie:

    https://YOUR-FIREBASE.firebaseio.com/users/name/first-name

## Note

The Firebase document is initiaized once the firebase-root is provided.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

firebase-input depends only on standard polymer elements from Google

## Related

firebase-input is designed for use inside of [firebase-card](https://heka-house-firebase-card-demo.firebaseapp.com)
