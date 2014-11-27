Bits
====

Bits (formerly Project BlackNode) is a custom wallet built on top of the existing Blackcoin protocol. Bits will focus on making Blackcoin simple enough for the technology-impaired to use cryptocurrency. Simplicity will be acheived through developed and intuitive UI design in combination with multisignature wallets and decentralized key-value store systems. 

Bits will be compatible with the Satoshi wallet or other wallet software—users will be able to send and receive Blackcoins to and from any Blackcoin address.

**Decentralized Address Resolution**

Bits provides a way to associate a cryptocurrency address to an email address or other identifier stored in a secure decentralized database. Transferring money through Bits will only require you to know the recipient's identifier without needing to have previously contacted them.

Address resolution will work similar to domain names. A user will be able to register an identifier to a public address for a set time period, with the option to revoke the association upon request.

We have been looking to GNUnet and Namecoin for example implementations of distributed key value store. Specifics of our design will be released soon in a project outline.

**Multi-signature Storage**

Bits is built around the concept of multi-signature wallets, which enables users to safely store and recover coins. The wallets are encrypted and backed up across trusted peers, or optionally in decentralized storage. In the event your device is lost or destroyed, select trusted personal contacts will be able to recover the encrypted wallet, and if your password is forgotten, your chosen family members or friends will together be able to decrypt the wallet.

**Smart Contracts**

Create secure contracts locally or with users around the world. Using Bits users can establish algorithmically self-enforceable contracts between two or more people to safely trade goods or services without the need for centralized services.

**Geolocal Storefronts**

Bits will make Blackcoin into the world's first decentralized geolocal cryptocurrency. Users are empowered to easily buy and sell goods in their local community using Blackcoin.

Using Bits, merchants will be able to create pop-up storefronts visible to users in their area. Customers can choose to search inventories of stores in their area and pay for goods or services with Blackcoin ahead of time, with or without a smart contract, or walk into a store to browse and shop in person like they could with cash. Blackcoin features 10 second transaction intervals and as it reaches greater distribution secure confirmation can happen as quickly or quicker than a credit card.

Decentralized encrypted geolocal chat will allow customers and merchants to communicate throughout the entire process.

**Geolocal Exchange**

Bits facilitates the negotiations and is capable of matching trades between cryptocurrency and national currencies. Users can search locally or world wide for trades that can be completed in person or through smart contracts.

In person exchange will allow quick payments facilliated by the incredible transaction speeds offered by Blackcoin. Tips, donation, and purchases will be easy and securely made to anyone in the geolocal area or worldwide.

**Quorum Sensing**

Bits is capable of detecting other Bits users in a geolocal area based on pre-existing trust relationships and user privacy settings. Upon reaching specific population density thresholds new features are enabled.

*When two or more users are within range:*

* Private encrypted communication will be available.
* Form joint accounts with with one or more users.

*When three or more users are within range:*

* Private encrypted group chat will be available.
* Users can start a key signing party to create a circle of trust or expand existing webs of trust.
* Users can opt to send or receive encrypted one-to-many broadcasts if they are within a circle of trust.

*When ten or more users are within range:*

* Users will have many tools available to facilitate organization of large groups of people:

  * Tools for protestors or other large groups of people to safely and securely organize.
  * Tools to raise funds and manage them transparently.
  * Tools to issue digital tickets confirmable through NFC enabled devices or QR code.
  * Tools to break up a Blackcoin and automatically send it to all participating users within a defined range or circle of trust to be used as ballots in a secure vote.

**Mesh Networking**

Bits is built on top of mesh networking tools that allow users to participate in trades, discussions, and voting—even in the absence of internet access—given enough users are within range.

**Full Featured API**

The Bits API will allow users to build plugins that leverage the Bits framework and quorum sensing tools for modular, expanded functionality.

**Road Map**

1. Publish project outline
2. Ready existing codebase for an open source alpha release
3. Open discussion about which open source libraries on projects we currently utilize to acheive our goals and if anyone from the community can offer better options.

**License**

Bits - Bits Geolocal Cryptocurrency Wallet
Copyright (C) 2014 Blackwave Labs

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
