# Bitcoin Merchant starter kit
![Bitcoin Logo](https://gitlab.com/nolim1t/bitcoin-merchant-starter-kit/-/raw/master/bitcoin-small.png)

The purpose of this project is to provide awareness of how merchants can accept Bitcoin payments.

There are multiple ways of doing this. At the easiest and quickest way, we recommend using mobile wallets.

But the best way is to use an actual server solution.

There is no right or wrong.

## Table of Contents

* [Mobile Wallets](#mobile-wallets)
    * [What coins to accept](#what-coins-to-accept)
    * [Setting up a mobile wallet](#setting-up-a-mobile-wallet)
* [Server based Wallets](#server-based)
* [POS Integration / Processing](#processing-the-payment-and-integration)
* [Offloading the coins](#offloading-the-coins)
* [Existing Merchants](#existing-merchants)
* [Maintainer notes](#maintainers-notes)
    * [Making Changes](#changes)
    * [Site mirrors](#mirrors)
    * [Contacting the Maintainer](#contact-info)

## Mobile Wallets

The easiest solution is to have a dedicated phone set up for receiving payments.

As most people know how to use a smartphone.

* [Breez Wallet](https://breez.technology/) - For accepting **Bitcoin Lightning** payments. You can set up prices for your items in the app too. Available on Android and iOS.
* [Coinnomi Wallet](https://www.coinomi.com/en/) - For accepting **on chain** payments. Available on Android and iOS.
* [Phoenix Wallet](https://phoenix.acinq.co/) - For accepting lightning payments. However this is Android only. I don't know what the latest user experience for this is like at this time.

### What coins to accept

On determining which coins to accept with Coinomi wallet, you should always check the general liquidity in your area and also the demand on people to want those coins.

There is no right or wrong, however the most commonly traded ones in terms of volume are:

* Bitcoin (BTC)
* Ethereum (ETH)
* Tether (USDT) / USD Coin (USDC)
* Bitcoin Cash (BCH)
* Litecoin (LTC)

But this is also up to the local market.

You can't really go too wrong with Bitcoin (BTC), Ethereum (ETH) and Stablecoins (USDC/USDT).

However, personally I would just stick with just Bitcoin (BTC) as its easier to find people / exchanges to trade with.

### Setting up a mobile wallet

When setting up a mobile wallet, It is important that you have a pen and paper handy to write down the backup phrases.

It is safe enough to keep this with the cash register for now as the amount of cash in the cash register probably will exceed the amount of cash in the bitcoin wallet.

You can also move most of the funds to your own personal wallet after it is above a certain amount for safekeeping.

## Server Based

With a repurposed laptop or Raspberry PI with at least 600 GB worth of space, I recommend using the [Umbrel](https://getumbrel.com) project.

This requires a little bit of technical chops, but it offers the best first class experience for bitcoin and lightning users. Not to mention access to this is available on any web browser.

But you must be able to consult someone locally for this type of method if you are not sure or to go ahead with this.

Another alternative which requires a little more knowledge is [BTCPayserver](https://btcpayserver.org/). This is probably a bit better than the Umbrel project, but requires more technical ability to get set up.

Other full node solutions of various difficulty and ease of use are:

* [MyNodeBTC](https://mynodebtc.com/)
* [RaspiBlitz](https://github.com/rootzoll/raspiblitz) - The oldest and most battle-tested.

## Processing the payment and Integration

The best thing to do with existing point of sale systems is to treat this as a CASH sale.

I've set up 2 businesses for this and they do this already.

The only difference is the cash does not get stored in the till, and the use of an additional app.

## Offloading the coins

We recommend due to the low volume of transactions and the potential of them increasing in value, that you hold on to the coins until you are able to spend them locally with ease.

Think of it as small savings.

Eventually the plan is to create a closed loop economy where there is enough services and goods to sustain this.

Thank you for being an early adopter!

The next best option would be to use [Nexo](https://nexo.io) to obtain a cash loan based on your crypto assets to manage cashflow. This requires that you verify your identity but it gives you the ability to realize the money as a loan which means it does not attract any capital gains taxes.

Otherwise, you may also use an exchange such as [Binance](https://binance.com/) to convert the coins over to USDC or USDT where you can sell it locally, or to preserve the dollar valley if you prefer to.

Or you can sell it locally through someone you've met or trust in the local community.

A good local option that might be available to you use [HODLHODL](https://hodlhodl.com/join/LTZA) or [BISQ](http://bisq.network/).

Whatever option you pick, you should consult someone in the local community for the best advice depending on your situation.

## Existing Merchants

If you have built your business, few free to be requested to be added to [the following list](https://nolim1t.gitlab.io/bitcoin-merchants/). You are required to show proof that you have done so too, or have someone show proof.

As a merchant taking Bitcoin (and other peer to peer assets), you should also try to offer a promotion for doing so.

Given that the price will increase in the long run, most people may not want to let go of their coins, but a small discount or another offer may see otherwise.

## Maintainers Notes

If you want to add to this document please see the below. Including mirroring, and contact information. This document is governed by the [Unlicense](https://nolim1t.gitlab.io/bitcoin-merchant-starter-kit/license/) License.

### Changes

Please open a [new issue](https://gitlab.com/nolim1t/bitcoin-merchant-starter-kit/-/issues/new) with the change you would like to add.

Or if you are more technical, you may [fork this project](https://gitlab.com/nolim1t/bitcoin-merchant-starter-kit/-/forks/new) and open a [merge request](https://gitlab.com/nolim1t/bitcoin-merchant-starter-kit/-/merge_requests/new).

Any changes to the repositories are automatically reflected on the site almost immediately.

### Mirrors

Because we love decentralization, this project is available in the public domain on the following sites:

* [Gitlab Repository](https://gitlab.com/nolim1t/bitcoin-merchant-starter-kit)
* [Github Repository](https://github.com/nolim1t/bitcoin-merchant-starter-kit)
* [Website on Gitlab Pages](https://nolim1t.gitlab.io/bitcoin-merchant-starter-kit/)

### Contact Info

The current maintainer of this page can be contacted through email (PGP Key: [0xf6287b82CC84bcbd](https://keys.openpgp.org/search?q=f6287b82CC84bcbd)) or on [mastodon](https://social.nolim1t.co/@nolim1t)
