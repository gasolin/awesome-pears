## **Awesome Pears 🍐**

A collection of awesome things regarding the Pears ecosystem.

- [Pears](#pears)
  - [Pears General Resources](#pears-general-resources)
  - [Pears Tutorials](#pears-tutorials)
- [Keet Public Rooms](#keet-public-rooms)
- [Building Blocks](#building-blocks)

### Pears

#### Pears General Resources
- [Pears website](https://pears.com/)
- [Pears Official Documentation](https://docs.pears.com/) [Source](https://github.com/holepunchto/pear-docs)
- [Pear Source Code](https://github.com/holepunchto/pear)
- [Holepunch](https://holepunch.to/) - Company who invent the Pears

#### Pears Tutorials

##### Article
- [Getting Start Pears](https://docs.pears.com/guides/getting-started)

##### Video
- [Build with Pear 🍐](https://www.youtube.com/watch?v=y2G97xz78gU&list=PLEZwCXa1K8Q629mWmpcSYCVMDoi0s8hzI) series


#### Pears Desktop
- run `npm i -g pear` to install the pear command ([nodejs](https://nodejs.org/) is required)
- Pear runtime - self contained Pear runtime
  - ```sh
    pear run pear://runtime
    ``` 
- [Keet.io](https://keet.io/) - P2P Instent Messenger
  - ```sh
    pear run pear://keet
    ```
- [pear-radio](https://github.com/holepunchto/pear-radio) - P2P music audio player/streamer
  - ```sh
    pear run pear://npyi57u7d7wx3frz5bnxaue7s44miwmyxy86tidtuxkq8axyf1io
    ```
- [File Sharing React example](https://github.com/holepunchto/filesharing-react-app-example)
- [PearPass](https://github.com/MKPLKN/peer-pass-backend) - your digital life manager, Pure P2P, everything is encrypted by default.
- [pearpass-example](https://github.com/holepunchto/pearpass-example) - pearpass with autobase
- [pear-expo](https://github.com/gasolin/pear-expo) - React Native web (Expo) setup for pear desktop
- [hyperclip-desktop](https://github.com/holepunchto/hyperclip-desktop)
- [PeerViewer](https://peerviewer.org/) - Direct, Secure and Uninterrupted Remote Access - The P2P Way
- [SeekDeep](https://github.com/noubre/seekdeep) - pear app interfaces with a local LLM

#### Pears Mobile

- [Keet.io](https://keet.io/) - P2P Instent Messenger
- [pear-expo-hello-world](https://github.com/holepunchto/pear-expo-hello-world) - (Deprecated) A Pear Runtime hello world using Bare with Expo
- [bare-expo](https://github.com/holepunchto/bare-expo) - Example of embedding Bare in an Expo application using bare-kit

##### Android

- [bare-android](https://github.com/holepunchto/bare-android) - Example of embedding Bare in an Android application
- [hyperclip-android](https://github.com/holepunchto/hyperclip-android) - send clipboard content from Desktop to Android
 
##### iOS

- [bare-ios](https://github.com/holepunchto/bare-ios) - Example of embedding Bare in an iOS application
- [hyperclip-ios](https://github.com/holepunchto/hyperclip-ios) - send clipboard content from Desktop to iOS

#### Pears Terminal
- Pear Runtime runs on [bare](https://github.com/holepunchto/bare), which is a cross-platform (including mobile) minimal JS runtime.
- 🔧 [Bare Node](https://github.com/holepunchto/bare-node) - a Node.js Compat builtins modules to easier reuse normal node modules with bare runtime
- [Compatibility config for node stdlib](https://docs.pears.com/bare-reference/nodejs-compatibility-with-bare#config-for-the-node.js-stdlib) - config to compatible with node standard libraries
- [bare-kit](https://github.com/holepunchto/bare-kit) - a web worker-like API to start and manage an isolated Bare thread, exposes an RPC abstraction with bindings for various languages
- [brokeout room](https://github.com/ryanramage/breakout-room/tree/autobase) - create small short lived rooms in a p2p space

### App that also use Hypercore (but not pear)

- [blogging](https://github.com/rukmani887799/blogging) - simple blogging site using hyperbee
- [holesail](https://holesail.io/docs/introduction) - Create P2P tunnels instantly that bypass any network, firewall, NAT restrictions and expose your local network to the internet securely, no Dynamic DNS required.
- [kiwi](https://github.com/nexhero/Kiwi) - The server enables access to its resources outside a local network, allowing users to connect from anywhere in the world.
- [hyperbeam](https://github.com/holepunchto/hyperbeam) - A 1-1 end-to-end encrypted file transfer tool
- [mapeo](https://www.digital-democracy.org/mapeo) - Mapeo is a free digital toolset for documenting, monitoring, and mapping many types of data
- [peerviewer](https://peerviewer.org/) - P2P remote desktop access
- [trollbox](https://www.peertopeerhub.com/trollbox) - P2P trollbox that anyone can access

### Keet Public Rooms

See [Keet Public Rooms](keet_rooms.md)

> Require install [Keet](https://keet.io) to join the room
> Can fork [keetlink](https://github.com/gasolin/keetlink) to share keet room invite via web (http)

### Building Blocks

- [hyperdht](https://docs.pears.com/building-blocks/hyperdht) - 1-on-1 connection by a public key, not by an IP [Tutorial](https://docs.pears.com/how-tos/connect-two-peers-by-key-with-hyperdht)
  - [hyperswam](https://docs.pears.com/building-blocks/hyperswarm) - discover and connect peers with a shared interest over a distributed network [Tutorial](https://docs.pears.com/how-tos/connect-to-many-peers-by-topic-with-hyperswarm)
- [hypercore](https://docs.pears.com/building-blocks/hypercore) - feed for sharing large datasets and streams of real-time data [Tutorial](https://docs.pears.com/how-tos/replicate-and-persist-with-hypercore)
  - [corestore](https://docs.pears.com/building-blocks/corestore) - manage multiple named hypercores [Tutorial](https://docs.pears.com/how-tos/work-with-many-hypercores-using-corestore)
  - [hyperbee](https://docs.pears.com/building-blocks/hyperbee) - log-like(append-only) key-value database [Tutorial](https://docs.pears.com/how-tos/share-append-only-databases-with-hyperbee)
  - [hyperdrive](https://docs.pears.com/building-blocks/hyperdrive) - a secure, real-time easy P2P file sharing [Tutorial](https://docs.pears.com/how-tos/create-a-full-peer-to-peer-filesystem-with-hyperdrive)
  - [hyperdb](https://github.com/holepunchto/hyperdb) - Database built for P2P and local indexing
    - [hyperdb-helper](https://github.com/brandtcormorant/hyperdb-helper) - Generate & build hyperdb schema definitions
  - [P2P indexing and search Tutorial](https://github.com/hypercore-protocol/p2p-indexing-and-search)
  - [autobase](https://github.com/holepunchto/autobase) - multiwriter data structures with Hypercore
- typescript type definition for hypercore and related modules - [1](https://github.com/digidem/digidem-types/tree/main/vendor) 
[2](https://github.com/digidem/mapeo-core-next/tree/main/types)
- [hyper-sdk](https://github.com/RangerMauve/hyper-sdk) - Software Development Kit for the hypercore-protocol
- [nebula](https://github.com/Telios-org/nebula) - Nebula drives are real-time distributed storage for files and key value databases
- [ouroboros](https://github.com/lejeunerenard/ouroboros) - define derived indexes on autobase hyperbees
- [pouchdb-adapter-hyperbee](https://github.com/RangerMauve/pouchdb-adapter-hyperbee) - Adapter for PouchDB to load p2p data from Hyperbee
- [agreeable](https://github.com/ryanramage/agreeable) - Type friendly agreements between peers for rpc and forms
- [AutoPass](https://github.com/holepunchto/autopass) - Multiwriter password and note sharing module

### Building Blocks Tutorials

- [Building Collaborative P2P Applications with Autobase](https://github.com/hypercore-protocol/p2p-multiwriter-with-autobase/tree/main) mentioned hyperdht, hyperswarm, hypercore, and autobase

### Contribution

We focus on sharing entirely free resources here. Please feel free to propose updates for outdated projects and articles, as well as new contributions. Your input and suggestions are wholeheartedly♡ appreciated. (✿◠‿◠)

[![CC0](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
