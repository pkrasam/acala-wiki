# Transaction Fees

Transaction fees are used to prevent users from consuming too much limited resources of the blockchain, such as storage and computation power. Karura uses weight-based fees, unlike gas, are predictable and charged pre-dispatch. 

### Fee Estimates

These are rough estimates of typical relevant transactions:

* **Inter Kusama and Karura transfer,** there are two components to the cross-chain transfer fees:
  * Kusama fee, determined by Kusama
  * Karura fee: 8 milliKAR
* **Karura** 
  * **Transfer:** 4 milliKAR
  * **DeX swap:** 12 milliKAR
  * **Add liquidity:** 18 milliKAR
  * **Adjust kUSD loan:** 18 milliKAR

Note: these are estimates and will be changed based on actual transaction size, network conditions and other factors.

### Fee Adjustment <a id="fee-adjustment"></a>

Fees on Karura are adjusted based on transaction volume, while still predictable. Karura has a block fullness target, fees increase or decrease for the next block based on the fullness of the current block relative to the target. 

### Bring Your Own Gas

Why users are restricted to pay fees in the native token when transferring other tokens?! On Karura you don't need to. Users can pay fees in any tokens that are supported on the Karura network. When paying fees in tokens other than KAR, fees are still estimated in KAR, a real-time swap operation \(between paid token and KAR\) is executed automatically by the chain. This operation is atomic and transparent to the users. 

