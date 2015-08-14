# Deploying Rocket.Chat to sloppy.io

![sloppy.io logo](http://sloppy.io/wp-content/uploads/2014/04/sloppy-icon.png)

[sloppy.io](http://sloppy.io) is a CaaS (Container as a Service) Provider. You can deploy, scale and manage your dockerized applications in seconds. [Try it for free](http://sloppy.io/#signup) 

## Start it

```
sloppy start rocketchat.json  -var=USERNAME:yourusername,URI:mydomain.sloppy.zone
   
Example:
   
sloppy start rocketchat.json  -var=USERNAME:john,URI:coolchat.sloppy.zone
```