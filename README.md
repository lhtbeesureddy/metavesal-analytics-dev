# metavesal-analytics-sdk
    AppStore-sdk can be used to build AI Apps compatible to AI-appstore, It Contains functions to configure and receive the camera feed in App using AMQP protocol.
 
## Getting-Started
  metavesal-analytics-sdk is a library and can be installed using npm.
  
#### Prerequisites
   * Nodejs need to be installed.
   
## Installing
 npm i metavesal-analytics-sdk
 
## Functions
### connect :  
  This Functions need to be called first, when application starts, its need three parameters:  
  1. UserID: which Developer get when he create account at AI app-store.  
  2. App-Id: your app-id which you get at AI appstore.  
  3. callbackfunction: this function triggers continiously whenever rabbitMQ listener got a call from AI App-Store(which contains the list of faces, their timestamps, madID and callbackIdentifier).  

### analyticsData :  
  This Functions need to be called first, when application starts, its need three parameters:  
  1. UserID: which Developer get when he create account at AI app-store.  
  2. App-Id: your app-id which you get at AI appstore.  
  3. callbackfunction: this function triggers continiously whenever rabbitMQ listener got a call from AI App-Store(which contains the list of faces, their timestamps, madID and callbackIdentifier).  # metavesal-analytics-js-sdk
