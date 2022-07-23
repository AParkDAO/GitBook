# Initial Network Unity

## Alpha State

The initial network features a one-way Cave (money goes in, none comes out), the Bargain contract (through which supply increases and profits are produced), and the Unityg contract (where profits are distributed). The following are the initial policy states:

* **BCV**

BCV varies based on Bargain types. It is tuned regularly by the Policy team to meet the protocol goals. For example, if the protocol wants to accumulate more liquidity into its Cave, it can lower the BCV for liquidity Bargain to increase their capacity.

* **Bargain vesting term**

It is set to 1,512,000 BNB Chain blocks or approximately 14 days for all Bargain types.

* **APD distribution**

Every time someone purchases a Bargain, the proceed will go to the Cave. A corresponding amount of APD will be minted and distributed to three parties:

* **Bargain purchaser**

The Bargain purchaser will receive the quoted amount of APD linearly over the vesting term.

* **DAO**

The DAO receives the same amount of APD as the Bargain purchaser. This represents the DAO profit.

* **Unity Participan**

After accounting for the APD distributed to the Bargain purchaser and the DAO, the rest will be distributed among all Unity participants in the protocol.
