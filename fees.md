# Fees

To place order on the DEX one has to pay network fees. Using the ARC0017 seller pays 0,006 algo \~ $ 0,002 and executioner pays 0,002 algo \~ $ 0,0006

DiatomiX main stream of revenue will be from providing interesting market pairs and option assets.

Market maker (seller of asset1):

Sum: 0.006 algo, 0.2 algo while order is live

* Before trade&#x20;
  * Send minimum algo balance (0.2 algo) - fee (0.001 algo)
  * Opt in to asset 1 (0.001 algo)
  * Send asset 1 to escrow account (0.001 algo)
* Close order
  * Proof of ownership (0.001 algo)
  * Send close algo tx  (0.001 algo)
  * Send close asset 1 tx  (0.001 algo)

Market taker:

Sum: 0.002 algo, no other fees or collateral

* Take asset 1 from escrow&#x20;
* Pay asset 2 to seller
