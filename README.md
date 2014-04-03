contact-cordova
===============

## Instructions

### Deploy the backend

Follow these instructions : https://github.com/jboss-developer/jboss-wfk-quickstarts/tree/2.6.x-develop/contacts-mobile-basic




### Build the client

```
git clone https://github.com/sebastienblanc/contact-cordova
cd contact-cordova
cordova platform add android

```

in ``` www/js/app.js ``` point  ``` APPMODULE.app.restEndpoint ``` to your backend URL

then just run : 

```
cordova run android

```



