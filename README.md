### HTMX + Go experiment

This is just a stupid todo-like project made to explore the symbiosis between HTMX and a Golang (echo) mvc app.

(For the sake of curiosity)

Although it's not an approach I would use in the projects I usually deal with daily, this model certainly gives me some interesting ideas for certain scenarios. I feel that this combination makes sense for monolithic/MVC projects, where the front end and back end are a single entity, projects with server-side rendering that use templating tools to build the HTML. With this, we can add interactivity to the view while maintaining 100% synchronization with the server, ensuring that what is being rendered on the screen is truly a reflection of the state controlled by the server.

![GaRbAGe](https://github.com/Timfts/blog/assets/17283501/50212cdd-9740-4e0e-90f5-3f5e59cf2788)
