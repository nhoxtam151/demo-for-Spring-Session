### DEMO FOR SPRING SESSION

## There is a problem with the default session handling. When the application is restarted, you will have to log in again, as the previous session data is lost. This is because the session is tied to the application server (Tomcat as default) and is not persisted across server restarts.
## This can be even more problematic in a horizontally scaled environment where multiple instances of an application are running. In such cases, a user's session might not be available if they're connected to a different instance of the application.
## The original session is tight to our single server, if we restart our server or we horizontal scale our systems, it properly not recognize the session, Spring session is gonna solve this problem for us.
