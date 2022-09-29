---
title: First Cypher Union 
---

<div style="width: 100%; background-color: #fe5186; color: black; padding: 10px; border-radius: 5px">
    Please note that this demo is an early preview and does not provide dependable privacy and safety of funds yet.
    <a href="#caveats"> Please see the caveats below.</a>
</div>

This is a first public Federate Chaumian E-Cash Mint on Bitcoin powered by [Fedimint](https://fedimint.org).
Check out [fedimint.org](https://fedimint.org) to learn how it enables privacy-preserving community banking on Bitcoin.

This instance is a demo for [#HCPP22](https://last-shot.hcpp.cz/), come by and check out our workshop area behind the
Bitcoin Cafe on the ground floor (go towards the stairs but walk past them and then take the door to the left).
We'll show you how to set up a wallet and give you some free sats for your first e-cash powered, private coffee purchase!

## How to use
<figure style="max-width: 350px; float: right; margin-top: 0; margin-left: 20px; margin-right: 20px;">
    <img src="img/federation_qr.png" alt="QR code to join the federation" style="border-radius: 8px;">
    <figcaption class="bottom">Federation code: <input value='{"members":[[0,"wss://hcpp.cypheru.net/"]]}' style="width: 100%"></figcaption>
</figure>

There are multiple ways to interact with this Fedimint instance. The main supported one is via the [Fluttermint mobile app](https://github.com/futurepaul/fluttermint). You can:

* [Download the APK](https://github.com/futurepaul/fluttermint/releases/download/0.1.0/app-release.apk)
* [Join iOS testflight](https://testflight.apple.com/join/Coep5PZS)

Once you installed the app it will ask you to scan or paste the federation code shown to the right to join this federation.

There are also some other options described on the [Fedimint Signet Faucet page](https://faucet.sirion.io/) but they are less user friendly.
If you want to try them out, come by, say hello and we can do some hacking together!

## Caveats
* This is beta-grade software, we can't make any availability guarantees but will give our best to keep it running during the conference.
* Please consider any personal funds sent to the wallet a donation. If you don't withdraw funds before this instance is shut down/migrated eventually all remaining funds will be donated.
* While e-cash has great privacy properties, none of the available clients has bulletproof privacy on the network layer. Lighning invoices can also leak meta-data since we haven't implemented all the privacy techniques at that layer yet.
* This is a 1-of-1 fake federation, if you want to experience the real deal come to our workshop on Friday 30th of September at 15:00 in the Institute of Cryptoanarchy.
