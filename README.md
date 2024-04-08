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
- [Keet.io](https://keet.io/) - P2P Instent Messenger
  - ```sh
    pear run pear://keet
    ```
- [pear-radio](https://github.com/holepunchto/pear-radio) - P2P music audio player/streamer
  - ```sh
    pear run pear://tnu5wefezcdj79st747ai45msrmdqaeyrhgcjpt4n1kkymwci51y
    ```
- [File Sharing React example](https://github.com/holepunchto/filesharing-react-app-example)


#### Pears Mobile
- [Keet.io](https://keet.io/) - P2P Instent Messenger
- [bare-android](https://github.com/holepunchto/bare-android) - Example of embedding Bare in an Android application
- [bare-ios](https://github.com/holepunchto/bare-ios) - Example of embedding Bare in an iOS application
- [pear-expo-hello-world](https://github.com/holepunchto/pear-expo-hello-world) - A Pear Runtime hello world using Bare with Expo
- [pear-expo](https://github.com/gasolin/pear-expo) - React Native web (Expo) setup for pear desktop

#### Pears Terminal
- Pear Runtime runs on [bare](https://github.com/holepunchto/bare), which is a cross-platform (including mobile) minimal JS runtime.
- 🔧 [Bare Node](https://github.com/holepunchto/bare-node) - a Node.js Compat builtins modules to easier reuse normal node modules with bare runtime

### App that also use Hypercore (but not pear)

- [mapeo](https://www.digital-democracy.org/mapeo) - Mapeo is a free digital toolset for documenting, monitoring, and mapping many types of data
- [peerviewer](https://peerviewer.org/) - P2P remote desktop access
- [blogging](https://github.com/rukmani887799/blogging) - simple blogging site using hyperbee

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
  - [P2P indexing and search Tutorial](https://github.com/hypercore-protocol/p2p-indexing-and-search)
  - [autobase](https://github.com/holepunchto/autobase) - multiwriter data structures with Hypercore
- typescript type definition for hypercore and related modules - [1](https://github.com/digidem/digidem-types/tree/main/vendor) 
[2](https://github.com/digidem/mapeo-core-next/tree/main/types)
- [hyper-sdk](https://github.com/RangerMauve/hyper-sdk) - Software Development Kit for the hypercore-protocol
- [nebula](https://github.com/Telios-org/nebula) - Nebula drives are real-time distributed storage for files and key value databases
- [ouroboros](https://github.com/lejeunerenard/ouroboros) - define derived indexes on autobase hyperbees
- [pouchdb-adapter-hyperbee](https://github.com/RangerMauve/pouchdb-adapter-hyperbee) - Adapter for PouchDB to load p2p data from Hyperbee
- [agreeable](https://github.com/ryanramage/agreeable) - Type friendly agreements between peers for rpc and forms
  
### Contribution

We focus on sharing entirely free resources here. Please feel free to propose updates for outdated projects and articles, as well as new contributions. Your input and suggestions are wholeheartedly♡ appreciated. (✿◠‿◠)

[![CC0](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
