Werkbank Demo Project
=====================


Hosted Applications
-------------------

In order to let you experience the final outcome first, the two applications build within this demo project are hosted at 
* http://s14.wservices.ch:61002/ParcelApp/    (pwd dan    try twice in case of connection pool error)
* http://s14.wservices.ch:61002/VaadinParcelApp/     (pwd dan    try twice in case of connection pool error)
 
Therefore you do not have setup a build environment or a deployment env to get a first impresseion.  Both apps are 
exactily identical regarding business logic and app structure (commands). However, there are two different ui - runtimes used. 
It might be very interessting, how such an app is modelled with the werkbank toolchain (especially ui / command / intterrelation).


Dev-Kit
-------

You can find the development kit at https://www.modellwerkstatt.org/xxwerk20ddd/javaexe.zip. This zip contains a fully 
configured MPS335, with necessary plugins, and the demo-project. The werkbank plugin has to be downloaded from 
https://github.com/danielstieger/moware35/releases/tag/2019.38 The post-office app itself is also hosted on git at 
https://github.com/danielstieger/postoffice Tomcat as a webserver is again packaged in the zip, in case you want 
to run the app as web-app locally. I would recommend the java-fx runtime for local experimentation. 

Not included ist the java runtime itselft. Typically we are using the last version not demanding any licenes (
https://www.oracle.com/technetwork/java/javase/downloads/java-archive-javase8-2177648.html) Additionally, mariadb as a database
is suggested when working localy. 

      
