# MetaHaven

An immersive virtual office .

MetaHaven works on all PC browsers (mobile browsers are currently not supported).

## Built with

- [Phaser3](https://github.com/photonstorm/phaser) - Game engine
- [Colyseus](https://github.com/colyseus/colyseus) - WebSocket-based server framework
- [React/Redux](https://github.com/facebook/react) - Front-end framework
- [PeerJS](https://github.com/peers/peerjs) - WebRTC for video/screen sharing
- [TypeScript](https://github.com/microsoft/TypeScript) and [ES6](https://github.com/eslint/eslint) - for both client and server sides

## Features

- Proximity Chat
- Flexible Screen Sharing
- Multifunctional Rooms
- Text Message Chat
- Custom/Private Rooms
- Embedded Whiteboards (iframe embed of [WBO](https://github.com/lovasoa/whitebophir))

## Controls

- `W, A, S, D, or arrow keys` to move (video chat will start if you are close to someone else)
- `E` to sit down
- `R` to use computer (for screen sharing)
- `Enter` to open chat
- `ESC` to close chat

## Prerequisites

You'll need [Node.js](https://nodejs.org/en/), [npm](https://www.npmjs.com/) installed.

## Getting Started

Clone this repository to your local machine:

```bash
git clone https://github.com/anishayh/MetaHaven.git
```

This will create a folder named `MetaHaven`. You can specify a different folder name like this:

```bash
git clone https://github.com/anishayh/MetaHaven.git my-folder-name
```

To start a server, go into the project folder and install dependencies/run start command:

```bash
cd MetaHaven or 'my-folder-name'
yarn && yarn start
```

To start a client, go into the client folder and install dependencies/run start command:

```bash
cd MetaHaven/client or 'my-folder-name/client'
yarn && yarn dev
```
## Hosting
Clients: Inside the root folder there is a netify.toml file. This makes it easy to deploy our client over on Netlify. All you have to do is connect the github repository and Netlify will do the rest following the instructions from the promo file.

Server: go to render  and deploy from Github link its to the netlify and add to your enviroment variables under VITE_SERVER_URL.


