# Asoplax.com
Official asoplax.com v0.0.1 alpha pre-release project blueprint.
Stay away from "dependency hell" :(


This is an open-source project aiming to the public unlimited, unrestricted free service and no data collection for later third-party software.
Must satisfy CIA requirements and ACID db requirements, the service should NOT rely on account creation in order to use the service, user account creation should only serve the unique purpose of more in-depth configuration on the site, but the user should be able to enter and interact with "all" website features except for those where account is really required.
Garbage collection must be integrated, and executed at a dynamic frequency synchronous with the thread state and *Asynchronous* within the top-node dispatcher, with an expected call frequency varying from [1h-24h], must also have public access to the central model properties and attributes, with ONLY [read] privilege, if mutation of a single component is expected or required a single reverse-lock is executed within its model, a one-time get-and-set cycle, and state variable reset to initial state. 


************************
*** Project stage: 1 ***
************************

********* Project stage table:*******

@stage 1: primary, initial stages, development, and alpha deployment.


@stage 2: delta factorization, socials ACs are added to the org, and final code factorization.


@stage 3: iOS app development and publishment.

/******************************/

The project required Technologies/frameworks:

---- Backend ----

@node
@express
@https
@ws/wss

---- Database ----
@mongodb


---- Frontend ----
@vanilla javascript
@typescript
@react


---- Style ----
@tailwindcss
@sass
@scss



---- Markup ----
@html
@xml


******** contact mode ********
@email

private: ...

public: 

       support@asoplax.com
       
       admin@asoplax.com
       
       bug@asoplax.com
       


******** Server *********

@software: Nginx(free mode)

@proxy: true

@reverse proxy: true

@load balancer: true

@proxy port: 9876



******** Attribution ********
@https://piesockets.com => for allowing us to better snd faster test, configure and develop websocket code.

@https://api-ninjas.com => for the coolest jokes out there, they're service is free so they at least deserve attribution :)

@https://geoapify.com => for the best geolocation service bring free and easy to implement.

@https://tailwindtoolbox.com => for the cool and free svg components used for asoplax developement.

@https://cssloaders.github.io => for the cool loaders on the website.

@https://flaticon.com => for the cool and free(althought limited by attribution) icons used on asoplax.

