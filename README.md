# MovieEnt

Browse The Movie Database using React as the Front End. The App is designed to be mainly used on Desktop, but it's fully mobile responsive. 

I built this app for myself so I could browse MovieDb extremely quick.

Built With React, Router 4. Redux is intentionally not used. The UI is a mix of Material UI and custom css. 

Uses a mix of ES6, ES2017. 

Be warned, this app contains very large components ON PURPOSE. 

All my projects are based as Follows:

-App.js is the main center. It contains the router, and the App.js is used as the main State Container. 
-My projects assume that the navbar is always in the app.js as that is the one part of that app that tends to stay consistent. 
    BrowserRouter
        Navbar
        RouterView(The routes or the pages are contained here)
        Footer

OPEN SOURCE IS LIFE