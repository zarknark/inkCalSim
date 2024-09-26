# inkCalSim: Life-Sim Game Framework powered by Ink & React

Goal: create a light, easy way to create text-based, planning-centric life simulation games

- Implement the build process. Someone should be able to:
    - put their .ink source files (not compiled JSON) in the `public/` folder
    - run `npm run package`

  and get a nice zipped HTML package in the `dist/` output, ready for itch.io. 
  
  Note: this process should also try to extract metadata from the source files and embed it into the index.html file.

- ~~draw the rest of the owl~~ Implement a barebones ink engine. This should be a responsive text interface friendly to both mobile and desktop displays with:
    - smooth text transitions
    - scrolling
    - choice menus

  Note: Shamelessly rip off the Disco Elysium text column UI.

- Implement special syntext support that would allow things like:
    - Fallen London-esque 'flavor' text for choices
    - Pyre-esque parentheticals for words

- Implement quirky save system. Browser cookies are _fine_, but what about a encoded image file???

- Polish the interface.
