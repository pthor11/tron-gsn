# tron-gsn

## Contracts

1. RelayRegistrar

2. StakeManager

3. Penalizer

4. Forwarder

5. RelayHub

6. Paymaster (TestPaymasterEverythingAccepted)

## Setup

1. Registering request type RelayRequest with suffix: RelayData relayData)RelayData(uint256 maxFeePerGas,uint256 maxPriorityFeePerGas,uint256 transactionCalldataGasUsed,address relayWorker,address paymaster,address forwarder,bytes paymasterData,uint256 clientId)

2. Registering domain separator GSN Relayed Transaction with version: 3

3. Deploying WrappedEthToken contract

4. Setting minimum stake of 1 TestWeth on Hub

5. Setting minimum stake of 0.000000000000000001 wEth

6. Naive Paymaster successfully funded, balance: 1

7. Registering GSN relayer at http://127.0.0.1:50913

8. Funding relayer

9. Staking relayer 1 wEth 

10. Wrapping 1 wEth

11. Approving 1 wEth to StakeManager

12. Authorizing relayer for hub