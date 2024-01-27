# Overview

- Source chain interacts with chainlink router smartcon to define destination
- The router uses CCIP to communicate to ANOTHER router contract on the destination contract

# Core Capabilities

- Token transfers across chain
- Arbitrary message -- can send data to a smartcon
- Programmable Tokne Transfers -- transfer tokens & instructions with what to do with those tokens

# Workflow 

- Offchain 
    - Comitting DON: commits transaction on destination chain 
    - Executing DON: Orders what's getting sent through and what to execute
    - Rish Managment Network: Monitoring the source and desintation tx's, as well as the consensus for the DONs 