# Holochain Projects

A curated list of awesome things related to Holochain Rust Project Development.

*Last updated: January 2026*

![Holochain](https://user-images.githubusercontent.com/3318070/59160477-da780580-8ac5-11e9-8331-242fed4a4242.png)

## Table of Contents
- [Core Infrastructure](#core-infrastructure)
- [Development Tools & Libraries](#development-tools--libraries)
- [Active Applications](#active-applications)
- [Collaboration & Social](#collaboration--social)
- [Economic & Supply Chain](#economic--supply-chain)
- [Developer Resources](#developer-resources)
- [Legacy Projects](#legacy-projects)

---

## Core Infrastructure

**Holochain**
The current, performant & industrial strength version of Holochain on Rust. The foundation for building distributed peer-to-peer applications.
https://github.com/holochain/holochain

**Holo**
Cloud hosting market for distributed applications. Provides hosting infrastructure for Holochain hApps.
https://holo.host/

**EdgeNode**
Holochain Edge Nodes for running decentralized hApps. Self-hosted infrastructure for the Holo network.
https://github.com/Holo-Host/edgenode

**Lair Keystore**
Secure key management for Holochain applications.
https://github.com/holochain/lair

---

## Development Tools & Libraries

**Holochain Scaffolding**
Scaffolding tool to quickly generate and modify Holochain applications. Essential for rapid hApp development.
https://github.com/holochain/scaffolding

**Tryorama**
Toolset to manage Holochain conductors and facilitate test scenarios for end-to-end testing.
https://github.com/holochain/tryorama

**Holochain Client JS**
A JavaScript/TypeScript client for the Holochain Conductor API. Essential for building web frontends.
https://github.com/holochain/holochain-client-js

**Holochain Client Rust**
A Rust client for the Holochain Conductor API for native applications.
https://github.com/holochain/holochain-client-rust

**Holochain Client Python**
A Python client for the Holochain Conductor API for Python-based applications.
https://github.com/holochain/holochain-client-python

**Holochain Client C#**
.NET & Unity Client for Holochain, enabling game and enterprise development.
https://github.com/holochain-open-dev/holochain-client-csharp

**Tauri Plugin Holochain**
Ship cross-platform peer-to-peer apps using Tauri and Holochain. Supports desktop and mobile platforms.
https://github.com/darksoil-studio/tauri-plugin-holochain

**Holochain Playground**
Interactive development and debugging environment for Holochain applications.
https://github.com/darksoil-studio/holochain-playground

**Electron Holochain Template**
Template for building Electron desktop applications with Holochain backend.
https://github.com/lightningrodlabs/electron-holochain-template

---

## Active Applications

### Project Management & Collaboration

**Acorn**
Open-source, peer-to-peer project management application. Designed as a scrum-alternative Agile Development Pattern for distributed teams.
https://github.com/lightningrodlabs/acorn

**Moss**
Creating group coherence with Holochain apps. Framework for building collaborative group applications.
https://github.com/lightningrodlabs/moss

**Where**
Tooling for group self-awareness on Holochain. Enables spatial organization and location-based collaboration.
https://github.com/lightningrodlabs/where

**Converge**
Criteria-driven decision making and deliberation platform built on Holochain.
https://github.com/lightningrodlabs/converge

### Social & Communication

**Mewsfeed**
Distributed microblogging platform with moderation features. A Twitter-like social media on Holochain.
https://github.com/GeekGene/mewsfeed

**AD4M (ADAM)**
Agent-centric social network and interoperability dApp framework by Coasys. Enables sense-making and social DNA.
https://github.com/coasys/ad4m

**Doom**
Video message app built with Holochain, Electron, and WebRTC for peer-to-peer video communication.
https://github.com/felri/doom

**Herddit**
P2P sub-group posting app on Holochain. Reddit-like functionality with distributed architecture.
https://github.com/mattyg/herddit

**Comet**
Holochain powered distributed Reddit-like application.
https://github.com/MightyAlex200/Comet

### Productivity & Data

**Sweet**
Spreadsheet application for Holochain. Collaborative data management.
https://github.com/lightningrodlabs/sweet

**Talking Stickies**
Collaborative sticky notes application built as a Holochain we-applet.
https://github.com/Holo-Host/talking-stickies

**REA Playspace**
Holochain app to experiment with REA (Resource-Event-Agent) accounting.
https://github.com/lightningrodlabs/rea-playspace

---

## Collaboration & Social

**Hylo**
A social network for community management, messaging and collaboration.
https://www.hylo.com

---

## Economic & Supply Chain

**hREA (HoloREA)**
A ValueFlows/REA economic network coordination system implemented on Holochain with GraphQL libraries. The leading economic coordination framework.
https://github.com/h-REA/hREA
https://hrea.io

**Sacred Capital**
Building the New Economy with reputation systems and mutual credit.
https://www.sacred.capital/

---

## Developer Resources

### Reusable Modules (Holochain Open Dev)

**Profiles**
Profile management zome for Holochain hApps with nickname support.
https://github.com/holochain-open-dev/profiles

**File Storage**
File Storage zome and UI module to store files in a Holochain DHT.
https://github.com/holochain-open-dev/file-storage

**Time Index**
Query Holochain DHT entries indexed according to time.
https://github.com/holochain-open-dev/holochain-time-index

**Peer Status**
Module to display the status of an agent (online, offline, busy, etc.).
https://github.com/holochain-open-dev/peer-status

**Y-Holochain**
Holochain provider for Yjs - build real-time p2p shared editor apps.
https://github.com/holochain-open-dev/y-holochain

**Holochain Open Dev Templates**
Templates to build modules and apps in the holochain-open-dev style.
https://github.com/holochain-open-dev/templates

### Lightning Rod Labs Tools

**Holochain Runner**
Wrapped Holochain Conductor with Status Update events and signal handling.
https://github.com/lightningrodlabs/holochain-runner

**HDK CRUD**
Library to quickly create CRUD functions for Entry types with time-based indexing and signaling.
https://github.com/lightningrodlabs/hdk_crud

**Attestations**
Verifiable claims in the Holochain world.
https://github.com/lightningrodlabs/attestations

### Other Resources

**Awesome Holochain**
Community-maintained curated list of Holochain resources, tools, and examples.
https://github.com/holochain-community-resources/awesome-holochain

**Cryptographic Autonomy License**
Open license protecting app developers, users, and end-user privacy and data control.
https://github.com/holochain/cryptographic-autonomy-license

**Deepkey**
Holochain core app to manage device and agent keys.
https://github.com/Holo-Host/deepkey-redux

---

## Legacy Projects

*These projects were part of the early Holochain ecosystem and may be inactive or deprecated.*

**Clutter**
Original fully distributed Twitter clone built on Holochain (archived).
https://github.com/holochain/clutter

**uprtcl (_Prtcl)**
Like Git, but for ideas and conversations.
https://github.com/uprtcl/js-uprtcl

**Minersweeper**
Massively Multiplayer Distributed Minesweeper on Holochain (archived demo).
https://github.com/holochain/minersweeper

---

## Contributing

Feel free to submit pull requests to add new projects or update existing ones. Please ensure projects are actively maintained and built on Holochain.

## License

This list is released under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
