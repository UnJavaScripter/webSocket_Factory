:octocat:
# webSocket_Factory
A Web Socket Factory for AngularJS

Usage
---
1- Include a reference to the webSocket_Factory.js file inside your index.html, like:
```html
<script src="scripts/webSocket_Factory.js"></script>
```
2- Include a reference to the module inside your app dependencies, like:
```javascript
angular.module("myAwesomeApp", ['unJS'])
```
3- Call it, like:
```javascript
webSocket_Factory.sendMessage('ws://echo.websocket.org', {"message": "Hey, socket!"});
```
You'll receive the response as a console.log(). For this example you'll receive back the message you sent inside the data property
