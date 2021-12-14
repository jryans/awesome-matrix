# Awesome Matrix [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of things related to the [Matrix](https://matrix.org/) ecosystem,
including software, research, etc. Matrix is an open protocol for secure,
decentralized data stores with a focus on communication.

This list hopes to become a good place for finding projects that may not have an
obvious category to fit into on the matrix.org website.

## Contents

- [Blogs](#blogs)
- [Bots](#bots)
  - [Multi Purpose Bot Platforms](#multi-purpose-bot-platforms)
  - [Single Purpose Bots](#single-purpose-bots)
- [Bridges](#bridges)
- [Clients](#clients)
- [Collaborative Documents](#collaborative-documents)
- [Comments](#comments)
- [Encryption](#encryption)
- [Factoids](#factoids)
- [Research](#research)
- [SDKs](#sdks)
- [Servers](#servers)
- [Testing](#testing)
- [Widgets](#widgets)

---

## Blogs

- [matrix-blog](https://evolved.systems/hosting-a-blog-on-matrix/) - A library
  to interact with a Matrix server in a way that treats it as a backend for a
  blog. ([Repo](https://github.com/evoL/matrix-blog),
  [Chat](https://matrix.to/#/#blog.hosting-a-blog-on-matrix:evolved.systems))
  `MIT` `TypeScript`

## Bots

### Multi Purpose Bot Platforms

- [maubot](https://maubot.xyz) - A plugin-based Matrix bot system with over 30
  plugins for all sorts of things. ([Repo](https://github.com/maubot/maubot),
  [Chat](https://matrix.to/#/#maubot:maunium.net)) `AGPL-3.0` `Python`
- [opsdroid](https://opsdroid.dev/) - A flexible multi-platform chat bot
  framework with Matrix support including end to end encryption.
  ([Repo](https://github.com/opsdroid/opsdroid),
  [Chat](https://matrix.to/#/#opsdroid-general:matrix.org)) `Apache-2.0`
  `Python`

### Single Purpose Bots

Some bots are quick scripts tailored to a specific purpose.

## Bridges

## Clients

For a comprehensive list with many more clients along with screenshots, the
[Matrix clients table](https://matrix.org/clients/) is a good resource.

- [Element](https://element.io) - A glossy client with an emphasis on
  performance and usability. ([Web](https://github.com/vector-im/element-web),
  [iOS](https://github.com/vector-im/element-ios),
  [Android](https://github.com/vector-im/element-android)) `Apache-2.0`
  `TypeScript`, `Swift`, `Kotlin`
- [FluffyChat](https://gitlab.com/famedly/fluffychat) - Cute instant messaging
  app for all platforms. ([Chat](https://matrix.to/#/#fluffychat:matrix.org))
  `AGPL-3.0` `Flutter`
- [Ditto](https://gitlab.com/ditto-chat/ditto) - React Native client for iOS and
  Android. ([Chat](https://matrix.to/#/#dittochat:matrix.org)) `GPL-3.0`
  `JavaScript`
- [Safesupport chatbox](https://github.com/nomadic-labs/safesupport-chatbox) -
  Embeddable Matrix chatbox.
- [Fractal](https://gitlab.gnome.org/GNOME/fractal/) - A client for GNOME
  written in Rust. ([Chat](https://matrix.to/#/#fractal:gnome.org)) `GPL-3.0`
  `Rust`

## Collaborative Documents

- [matrix-notepad](https://matrix-notepad.kb1rd.net) - A buggy way to
  collaborate on text documents using the Matrix protocol.
  ([Repo](https://github.com/KB1RD/matrix-notepad),
  [Chat](https://matrix.to/#/#matrix-collaboration:kb1rd.net)) `GPL-3.0`
  `JavaScript`
- [Populus-Viewer](https://opentower.github.io/populus-viewer/) - Social Annotation of PDFs,
  powered by Matrix. ([Repo](https://github.com/opentower/populus-viewer),
  [Chat](https://matrix.to/#/#opentower:matrix.org) `GPL-3.0`
- [TheBoard](https://toger5.github.io/TheBoard/) - Collaborative whiteboard
  powered by Matrix. ([Repo](https://github.com/toger5/TheBoard),
  [Chat](https://matrix.to/#/#TheBoard:matrix.org)) `MIT` `JavaScript`

## Comments

- [Cactus Comments](https://cactus.chat) - Federated, web-embeddable comment
  system for the open web built on Matrix.
  ([Repo](https://gitlab.com/cactus-comments/),
  [Chat](https://matrix.to/#/#cactus:bordum.dk)) `GPL-3.0` `Elm`, `Python`

## Encryption

- [Olm](https://gitlab.matrix.org/matrix-org/olm) - 
  Implementation of the Olm and Megolm cryptographic ratchets.
  `Apache-2.0` `C++`
- [pantalaimon](https://github.com/matrix-org/pantalaimon) - 
  E2EE aware proxy daemon for Matrix clients.
  ([Chat](https://matrix.to/#/#pantalaimon:matrix.org)) `Apache-2.0` `Python`

## Factoids

- [Matrix Limits](https://github.com/jryans/matrix-limits) - A collection of
  various limits and related factoids about the Matrix specification and
  implementations.

## Research

Research papers and similar documents studying something related to Matrix.

### 2021

- Matthew Weidner, Martin Kleppmann, Daniel Hugenroth, Alastair R. Beresford.
  [Key Agreement for Decentralized Secure Group Messaging with Strong Security
  Guarantees](https://eprint.iacr.org/2020/1281).
- Florian Jacob, Carolin Beer, Norbert Henze, Hannes Hartenstein. [Analysis of
  the Matrix Event Graph Replicated Data
  Type](https://arxiv.org/abs/2011.06488).

### 2020

- Florian Jacob, Luca Becker, Jan Grashöfer, Hannes Hartenstein. [Matrix
  Decomposition: Analysis of an Access Control Approach on Transaction-based
  DAGs without Finality](https://dl.acm.org/doi/10.1145/3381991.3395399).
- Martin Kleppmann, Heidi Howard. [Byzantine Eventual Consistency and the
  Fundamental Limits of Peer-to-Peer
  Databases](https://arxiv.org/abs/2012.00472).

### 2019

- Florian Jacob, Jan Grashöfer, Hannes Hartenstein. [A Glimpse of the Matrix:
  Scalability Issues of a New Message-Oriented Data Synchronization
  Middleware](https://arxiv.org/abs/1910.06295).
- Matthew Weidner. [Group Messaging for Secure Asynchronous
  Collaboration](https://mattweidner.com/acs-dissertation.pdf).
- Quirin Heiler, Richard von Seck, Jonas Jelten. [Peer-to-Peer
  Matrix](https://doi.org/10.2313/NET-2019-10-1_08).

### 2018

- Katriel Cohn-Gordon, Cas Cremers, Luke Garratt, Jon Millican, Kevin Milner.
  [On Ends-to-Ends Encryption: Asynchronous Group Messaging with Strong
  Security Guarantees](https://dl.acm.org/doi/10.1145/3243734.3243747).

### 2016

- Ksenia Ermoshina, Francesca Musiani, Harry Halpin. [End-to-End Encrypted
  Messaging Protocols: An
  Overview](https://doi.org/10.1007/978-3-319-45982-0_22).

## SDKs

- [matrix-rust-sdk](https://github.com/matrix-org/matrix-rust-sdk) - A modular
  SDK for writing Matrix clients, written in Rust. Implements Matrix E2EE in
  a separate crate with a [sans I/O](https://sans-io.readthedocs.io/) design.
  `Apache-2.0` `Rust`

## Servers

- [Synapse](https://github.com/matrix-org/synapse) - The reference homeserver.
  ([Chat](https://matrix.to/#/#synapse:matrix.org)) `Apache-2.0` `Python`
- [Dendrite](https://github.com/matrix-org/dendrite) - A second-generation
  Matrix homeserver written in Go. It intends to provide an efficient, reliable
  and scalable alternative. ([Chat](https://matrix.to/#/#dendrite:matrix.org))
  `Apache-2.0` `Go`
- [Conduit](https://conduit.rs) - A simple, fast and reliable chat server
  written in Rust. ([Repo](https://gitlab.com/famedly/conduit),
  [Chat](https://matrix.to/#/#conduit:matrix.org)) `Apache-2.0` `Rust`

## Testing

- [Patience](https://github.com/matrix-org/patience) - Full stack integration
  testing for Matrix clients and servers.
  ([Chat](https://matrix.to/#/#matrix-patience:matrix.org)) `Apache-2.0` `TypeScript`

## Widgets

- [matrix-widget-api](https://github.com/matrix-org/matrix-widget-api) - A widget
  API abstraction for browsers. ([Chat](https://matrix.to/#/#matrix-widgets:matrix.org))
  `Apache-2.0` `TypeScript`
- [matrix-widget-debug](https://github.com/turt2live/matrix-widget-debug) - Test
  widget for validating clients and `matrix-widget-api`. `Apache-2.0` `JavaScript`

---

## See Also

Various other directories and lists of Matrix things.

- [Try Matrix Now](https://matrix.org/docs/projects/try-matrix-now) -
  Comprehensive directory of various Matrix projects.
- [Matrix clients table](https://matrix.org/clients/) - Thorough list of many
  more Matrix clients along with screenshots.
- [@rodolpheh's awesome-matrix](https://github.com/rodolpheh/awesome-matrix) -
  An earlier effort at assembling awesome Matrix projects.

## Contribute

Contributions welcome! 😄 Read the [contribution guidelines](CONTRIBUTING.md)
first.

## License

Creative Commons Attribution 4.0 International
