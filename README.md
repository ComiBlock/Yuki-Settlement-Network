# Fiat network

This repository contains a prototype of the Yuki fiat network a connected ecosystem of on and off-ramps providers, allowing users to seamlessly ramp volumes between $10k to $500k. Here's a high-level overview of how it works:

## High level 

The Yuki fiat network would leverage orchestration On/Off ramp and OTC providers within Africa. These integrations would enable various liquidity partners across to easily settle ramp orders within the Yuki network.

## Requests for Off/On-Ramps:
When a business within the Yuki network or connected partners needs to perform a transaction; they would initiate a request through their interface which points them to the aggregated Ramp network provided by Yuki. This request would include all required transaction details.

## Broadcasting the Liquidity Request

Once a business off or on-ramp request is initiated, it will be broadcast across the entire aggregated On/Off ramp and OTC providers network. This broadcast serves to alert all liquidity providers within the network to fill the ramp order, we are doing this to be able to simplify the off or on ramping large amounts.

## Order Splitting

For large transactions, such as a $10,000 stablecoin on-ramp or fiat off-ramp, the system  automatically splits the transaction into smaller orders, such as $1,000 each. This splitting mechanism helps facilitate better and faster liquidity provision for this volume type.

## Request Execution and Settlement

Once a liquidity provider accepts a transaction request or order, they execute the transaction by providing the necessary liquidity from their fiat accounts connected to the Settlement network. order counterparty confirmation needed. While the crypto part is initiated via the Ramp Provider escrow account.

The Yuki Fiat network is still under development in partnership with various On/Off ramp providers connected to the Yuki ecosystem. 
