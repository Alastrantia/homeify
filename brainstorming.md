## ideas for homeify:
- ad free ofc
- tracking free
- highly customizable
    - draggable components 
    - custom accent colors
    - allow user to change html and css easily
- cozier than the real spotify, nicer greeting messages
- maybe a better feed
- self-hostable on a raspberry pi, even on the rpi02w like Invidious

## decisions to make
use spotify web api or same api frontend interacts with??

### tech stack?
    frontend:
        - maybe react or svelte, prolly react
    backend:
        - flask, expressjs and maaaaaaaybe django
        - just interact with the official api but don't do everything it does

maybe just clone the official spotify frontend, inspect the code and just change some styles and block some requests for ads etc.
    - nah thats for noobs