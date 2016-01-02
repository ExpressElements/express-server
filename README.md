 # express-server

 An simple element which spawns an express server.

 ### Usage:
 ```html
 <express-server port="8080">
   <express-route method="get" path="/" middleware="[[_home()]]"></express-route>
 </express-server>
 ```

 ...

 ```javascript
 _home = () => {
   return function (req, res) {
     res.send("hello world2");
   };
 }
```
