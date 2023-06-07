# Fiat network

This repository contains a prototype of the The Yuki fiat network a connected ecosystem for on and off-ramps, allowing users to seamlessly move between cryptocurrencies and fiat currencies. Here's a high-level overview of how it works:

## High level 

The Yuki fiat network would leverage integrations with payment fintech companies within the Yuki ecosystem. These integrations would enable users of various fintech partners to easily opt in as liquidity providers within the Yuki network.

## User Activation as Liquidity Providers

All crypto wallet owners offered by our Fintech partners within the Yuki API network would have the option to activate themselves as liquidity providers. By opting in, users indicate their willingness to provide liquidity services when other users within the ecosystem require an off or on-ramp.

## Requests for Off/On-Ramps:

When a user within the Yuki network or connected partners needs to perform an off or on-ramp transaction; they would initiate a request through their wallet which points them to the  dedicated Ramp interface provided by Yuki. This request would include all required transaction details.

## Broadcasting the Liquidity Request

Once a user's off or on-ramp request is initiated, it would be broadcasted across the entire Yuki fiat network. This broadcast serves to alert all liquidity providers within the network to fill the ramp order, we are doing this in order to be able to simplify the off or on ramping large amounts.

## Order Splitting

For large transactions, such as a $10,000 stablecoin on-ramp or fiat off-ramp, the system can automatically split the transaction into smaller orders, such as $1,000 each. This splitting mechanism helps facilitates better liquidity provision for larger transactions.

## Request Execution and Settlement

Once a liquidity provider accepts a transaction request or order, they execute the transaction by providing the necessary liquidity from their fiat accounts connected to the Fiat network through Yuki network of integrated partners using our API to offer crypto wallets. 
While the crypto part is initiated via the Yuki escrow account.


The Yuki Fiat network is still under development in partnership with Aladdin Bank 
