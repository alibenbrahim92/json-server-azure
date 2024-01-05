# json-server-for-azure
A json-server ready to be deployed on Azure App Service  
When a Node js app is deployed on Azure, this one will look for "start" command in package.json  
If it doesn't find it, it will run "node server.js"  
So we are using server.js, that will run json-server  
But it still need web.config to specify how the routes are handled  
