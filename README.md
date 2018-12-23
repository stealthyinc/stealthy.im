## Stealthy

Stealthy is a decentralized and encrypted communication protocol that empowers users to have a unified chat experience (think cross-platform & open iMessage). 

With Stealthy, developers can focus on building their dream dApp and offload the communication infrastructure to our protocol.

Homepage: https://www.stealthy.im

iOS Download: https://itunes.apple.com/us/app/stealthy-im/id1382310437?ls=1&mt=8

Android Download: https://play.google.com/store/apps/details?id=com.stealthy

## Motivation

This project stemmed from the increasing control companies place on user data. The big 4 tech companies control and leverage our data for profits without regard for our privacy or data safety.

Stealthy finally offers users a decentralized alternative to the status quo. With Stealthy, end users have a rich app experience not restricted by App Silos. At the same time, developers and content creators can reach a diverse network of users directly through our protocol.

Stealthy has a standalone mobile app that will soon be available in both the Apple and Google App store. Stealthy is open source and available for contributions. 

## Features Roadmap 

- [ ] Self-hosted Private Channels
- [ ] Share to Stealthy from 3rd party apps
- [ ] Electron Desktop App
- [ ] Stacks Wallet Integration
- [ ] Privately import contacts graph
- [ ] Integrate Gun DB
- [ ] Login with Stealthy
- [ ] Performance & UX improvements
- [ ] Messaging features: Group messaging, attachments, gifs etc
- [ ] Deeper dApp integrations: blog or post to social media from Stealthy

## Current Features (1.8)

- [x] iOS & Android Support
- [x] Public channels: topic discussion or dApp support
- [x] Private 1:1 messaging: client side encrypted for recipient
- [x] [iOS] Sharing and collaboration with other dApps (Graphite and Travelstack)

## Code

If you're just starting with Stealthy, here are the main software repositories you should checkout:

- [Stealthy Web App](https://github.com/stealthyim/webapp) - the implementation of Stealthy's web p2p chat product that won Blockstack's communication hackathon written in React JS.
- [Stealthy Mobile App](https://github.com/stealthyim/mobile) - the implementation of Stealthy's iOS/Android app that has dApp integrations, e2e chat, notifications, discovery, etc written in React Native JS (pending).

## Protocol Architecture

Stealthy has been used in production since March 2018 and currently has 5 dApp integrations. Our protocol works on web and mobile with cross platform support for encryption.

With the Stealthy communication protocol, dApps can communicate offline, real time (video, chat), and process transactions*. This is accomplished with a lite ledger methodology, only authentication requires blockchain, and the communication protocol is off-chain. This allows dApps to be as effecient (98%) as centralized counterparts. 

The Stealthy communication protocol is shown below:

<p>
<img src="https://www.stealthy.im/StealthyProtocolDiagram.svg" data-canonical-src="https://www.stealthy.im/StealthyProtocolDiagram.svg" />
</p>

## Social Graph & Contact Discovery

Stealthy uses public key encryption to setup communications between users. Standalone dApps need to setup a new network of users that need to login to the app before discovery/communications can begin.

With Stealthy, dApp partners get access to the social graph of Stealthy and other dApp partners immediately. The end user also benefits by being able to immediately collaborate with their existing contacts. This allows a larger audience for your dApp without the headaches of rebuilding the wheel each time.

## Developer Partnerships

If you're interested in building a communication centric dApp or add communication to your existing dApp, please reach out to us at [support@stealthy.im](mailto:support@stealthy.im).

## Contributing  

If you'd like to contribute to this project, there are a few ways to do so:

#### Report bugs
You can create a new issue any time, but please make sure your bug reports are clean and clear. Here's a good guide:

https://testlio.com/blog/the-ideal-bug-report/

Please make sure you search any existing issues for the bug you would like to report before opening a new issue.

#### Suggest Features
A public roadmap will soon be up at https://stealthy.im, but feature requests are always welcome. To suggest a feature, please open a new issue in this format:

Feature: [Your feature title]
Description of the feature requests

Be as detailed as possible in feature requests and be sure to search existing issues to make sure you are not making a duplicate feature request.

#### Bug Fixes
If you'd like to contribute by fixing any existing bugs, please create a pull request. Here's a basic guide for doing so:

https://help.github.com/articles/creating-a-pull-request/

## Cryptography Notice

This distribution includes cryptographic software. The country in which you currently reside may have restrictions on the import, possession, use, and/or re-export to another country, of encryption software. BEFORE using any encryption software, please check your country's laws, regulations and policies concerning the import, possession, or use, and re-export of encryption software, to see if this is permitted. See http://www.wassenaar.org/ for more information.

The U.S. Government Department of Commerce, Bureau of Industry and Security (BIS), has classified this software as Export Commodity Control Number (ECCN) 5D002.C.1, which includes information security software using or performing cryptographic functions with asymmetric algorithms. The form and manner of this distribution makes it eligible for export under the License Exception ENC Technology Software Unrestricted (TSU) exception (see the BIS Export Administration Regulations, Section 740.13) for both object code and source code.
