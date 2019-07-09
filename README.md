# JUKBOX

Jukbox is a digital replacement for traditional jukboxes - for decades music fans paid to have songs of thier choice played when visiting pubs or bars. It is a fast diminishing service, but a proven business model.

Jukebox allows venues to open up thier soundsystem to anyone with a web connected device and generate income at the same time.

The admin control panel generates tickets at a predefined inteval chosen by the venue and allows users to add songs to a playlist. Then using integrated payments through Stripe, users can purchase diamonds that allow them to move thier song to the top of the list, or if people are competing to have thier song played next, in to a paid for queue.

The user Dashboard shows a queue of songs that updates in realtime where they can interact with the playlist and see how long they have until they are due to recieve a new ticket from the venue.

Please reference the submodules above for front and back-end repos.

The app is currently being deployed for demo purposes.

## Screenshots

<p align="center">
  
  <img src='https://lh3.googleusercontent.com/fGtlYvbQtlgEBqby4dBSWNigsQBsXVlq7j6dEFIGSItEQesbqVgRwC7sSLx16pQq6vzRrknol-wnJDH65Uyew1s68_hu0wlD2WOtoW44Z_YfyRxsWEd8ZgHeoCOiuQ7uto2iTZ4qSw0=w2400' width="280px"/>
  
<img src='https://lh3.googleusercontent.com/hKpv6YU9kP1Sdmwe8VZ5-8sod5hNE1PDB92kKHL5y1cDrdJEn_o9QvC9fgDpvZQmJaxIn6cOca-kKFKs02CNTjvAjekEqiUEdr0mkukFJK-QVfQnjbrTsoHt53NGULA-q0Ax46LYnIw=w2400' width="280px"/>

<img src='https://lh3.googleusercontent.com/aJc-MH6WxTYPh3WJ9YteZEVxghsWJVAU-oBsCTOr-9ivqFemqpF6lc069BxfFMoxNFey1g4ZkP3F4JR6V3jNw5b2jQg4q5JQNYKyI7tOyH53VR-YZXbMp26HEuIq53PB5oZIrlLj6kE=w2400' width="280px"/>
  
</p>

## Details

Venues can connect to Jukbox by logging in with their Spotify premium credentials. Then it's as simple as pressing play to 
start hosting the music.


Users can then join a venue by logging in with a Google Account. Upon a successful connection, tickets are issued to each
user that can be redeemed for a song pick. 


As songs are requested, they get added to the bottom of the playlist. However, a user can opt to move a given song to 
the top of the list, by spending 'diamonds' which determine the order of the songs. Diamonds can be purchased through
Stripe, and are stored in the user's account.


## Tech Stack

* [React](https://reactjs.org/) - Frontend Framework
* [Redux](https://redux.js.org/) - State Management
* [Express](https://expressjs.com/) - Backend Framework 
* [PostgreSQL](https://www.postgresql.org/) - Database
* [Socket.io](https://socket.io/) - Web Sockets
* [Google Authentication](https://developers.google.com/identity/protocols/OAuth2)
* [Spotify API](https://developer.spotify.com/)
* [Stripe](https://stripe.com/docs) - Payment Processor
* [Typescript](https://www.typescriptlang.org/)

## Contributors 
* Tom Belton [GitHub](https://github.com/whenmoon) - [LinkedIn](https://www.linkedin.com/in/tom-belton-6193a3168/)
* Jozef Kysel [GitHub](https://github.com/JozefKysel) - [LinkedIn](https://www.linkedin.com/in/jozef-kysel-382ba6182)
* Katie Ramiré [GitHub](https://github.com/kramire) - [LinkedIn](https://www.linkedin.com/in/kramire/)
* Leander Rysanek [GitHub](https://github.com/leandroviajando)
* Matthew Tregear [GitHub](https://github.com/matthewtregg)
* Dorothée Viard [GitHub](https://github.com/Do0oV) - [LinkedIn](https://www.linkedin.com/in/dorotheeviard)
