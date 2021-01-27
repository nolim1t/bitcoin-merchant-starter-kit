# Bitcoin Merchant starter kit
![Bitcoin Logo](https://gitlab.com/nolim1t/bitcoin-merchant-starter-kit/-/raw/master/bitcoin-small.png)

The purpose of this project is to provide awareness of how merchants can accept Bitcoin payments.

There are multiple ways of doing this. At the easiest and quickest way, we recommend using mobile wallets.

## Table of Contents

Please see the following sections.

* [Mobile Wallets](#mobile-wallets)
    * [What coins to accept](#what-coins-to-accept)
* [Server based Wallets](#server-based)
* [POS Integration / Processing](#processing-the-payment-and-integration)
* [Offloading the coins](#offloading-the-coins)
* [Maintainer notes](#maintainers-notes)
* [Existing Merchants](#existing-merchants)

## Maintainers Notes

If you want to add to this document please see the below. Including mirroring.

### Housekeeping

#### Changes

Please open a [new issue](https://gitlab.com/nolim1t/bitcoin-merchant-starter-kit/-/issues/new) with the change you would like to add.

Or if you are more technical, you may fork this project and open a pull request.

#### Mirrors

This project is available in the public domain on the following sites:

* [Gitlab Repository](https://gitlab.com/nolim1t/bitcoin-merchant-starter-kit)
* [Website on Gitlab Pages](https://nolim1t.gitlab.io/bitcoin-merchant-starter-kit/)

## Mobile Wallets

The easiest solution is to have a dedicated phone set up for receiving payments. As most people know how to use the phone.

* [Breez Wallet](https://breez.technology/) - For accepting **Bitcoin Lightning** payments. You can set up prices for your items in the app too. Available on Android and iOS.
* [Coinnomi Wallet](https://www.coinomi.com/en/) - For accepting **on chain** payments. Available on Android and iOS.
* [Phoenix Wallet](https://phoenix.acinq.co/) - For accepting lightning payments. However this is Android only. 

### What coins to accept

On determining which coins to accept with Coinomi wallet, you should always check the general liquidity in your area (how much people alo want to keep these coins).

There is no right or wrong, however the most commonly traded ones in terms of volume are:

* Bitcoin (BTC)
* Ethereum (ETH)
* Tether (USDT)
* Bitcoin Cash (BCH)
* Litecoin (LTC)

But this is also up to the local market. You can't really go wrong with Bitcoin, Ethereum and Tether. 

Also please note that Tether is also pegged to the USD. It will follow the USD as opposed to your local currency. This may be good or bad.

### Setting up a mobile wallet

When setting up a mobile wallet, It is important that you have a pen and paper handy to write down the backup phrases.

It is safe enough to keep this with the cash register for now as the amount of cash in the cash register probably will exceed the amount of cash in the bitcoin wallet.

You can also move most of the funds to your own wallet after it is above a certain amount for safekeeping.

## Server Based

With a repurposed laptop or Raspberry PI with at least 600 GB worth of space, I recommend using the [Umbrel](https://getumbrel.com) project.

This requires a little bit of technical chops, but it offers the best first class experience for bitcoin and lightning users. Not to mention access to this is available on any web browser.

But you must be able to consult someone locally for this type of method if you are not sure or to go ahead with this.

## Processing the payment and Integration

The best thing to do with existing point of sale systems is to treat this as a CASH sale.

I've set up 2 businesses for this and they do this already. 

The only difference is the cash does not get stored in the till, and the use of an additional app.

## Offloading the coins

We recommend due to the low volume of transactions and the potential of them increasing in value, that you hold on to the coins.

Think of it as small savings.

Eventually the plan is to create a closed loop economy where there is enough services and goods to sustain this.

Thank you for being an early adopter!

The next best option would be to use [Nexo](https://nexo.io) to obtain a cash loan based on your crypto assets to manage cashflow.

Otherwise, you may also use an exchange such as [Binance](https://binance.com/) to convert the coins over to USDC or USDT where you can sell it locally.

Or you can sell it locally through someone you've met or trust in the local community.

A good local option that might be available to you use [HODLHODL](https://hodlhodl.com/join/LTZA) or [BISQ](http://bisq.network/).

Whatever option you pick, you should consult someone in the local community for the best advice depending on your situation.

## Existing Merchants

If you have built your business, few free to be requested to be added to [the following list](https://gitlab.com/nolim1t/bitcoin-merchants). You are required to show proof that you have done so too, or have someone show proof.

