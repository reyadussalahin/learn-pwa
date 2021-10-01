# PWA
The most concise guide to Progressive Web Applications



History of Apps before PWA
==========================

Advantages of native apps
-------------------------
1. Fast
2. Native feels(great rendering)
3. Works offline
4. Ease of use(In smart phones just a single click)
5. No need to track url
6. Push Notifications


Disadvantages of native apps
----------------------------
1. Need to built platform specific app(great cost)
2. Need to maintain multiple apps(for each platform) and implement each feature in each app
3. No SEO
4. Huge Size
5. Slow development
6. Complex upgrade system


Advantages of web apps
----------------------
1. Platform Independent(Works in Browser), so just a single app needs to maintained
2. Less cost
3. Fast development
4. Less Size
5. SEO
6. Easy to upgrade


Disadvantages of web apps
-------------------------
1. Browser dependent
2. Needs url to access
3. Missing native feels
4. Not fast/responsive enough
5. Missing push notifications
6. Does not work offline
7. No as easy as using native apps



Birth of PWA
============

Why PWA?
--------
If you notice carefully, you'd see that the advantages native apps provide, are actually the things web apps can't provide, and the advantages the web apps provide, the native apps are at a disadvantage on those things.

> PWA is here to solve the problems of both native and web apps by taking best of the both worlds.

What is a PWA?
--------------
But, what is a PWA?

Let's discuss what advantages a web app should provide to become a PWA:

1. It must progressively give native feels
2. It should be platform independent i.e. a single app should run every platform
3. It should provide a installation system like native apps and can be open like native apps
4. It should support push notifications like native apps
5. It should provide caching to work offline
6. The upgrade of app should be smoother than the native apps(like web apps)
7. It should take advantage of SEO

So, if any web app that could provide the above advantages, should be called `Progressive Web App`.



How PWA is implemented
======================
As you can imagine PWA's are web apps, but a special type of web apps. Below is given the constructs, which a web app uses or takes advantage of to become a PWA:

1. PWA takes advantage of browser runtime(that's why it can run anywhere)
2. PWA takes advantage of a browser construct called `Service Worker`
    - Service worker runs in a separate thread than the browser's main thread
    - Service worker can run in background(i.e. even when the browser is closed)
    - Service worker acts as a proxy between the browser and the network
    - Service worker uses cache to save assets locally or even dynamic pages for offline use(note: it's not the same as browser cache)
    - Service worker can subscribe for push notifications
3. PWA needs a manifest file to instruct the platform how the app is going to be installed in the system

Note: PWA is also a web app, so it has all the advantages of a web app



Disadvantages of PWA
====================



A Simple Demo
=============



LICENSE
=======



Contribution
============
