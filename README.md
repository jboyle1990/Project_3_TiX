
# Capstone Project -  NFT Ticketing Platform

## Executive Summary

Create a decentralized ticketing & digital merchandise platform to empower artists and creators to engage directly with fans through events and exclusive content. This platform would leverage blockchain technology,  lower fees, and customer loyalty to become the premier ticketing platform in the marketplace.

## Value Proposition:

Lower fees than traditional ticketing platforms
Secure transactions verified on the blockchain 
Royalty payments from merchandise + ticketing revenue for event organizer
Robust secondary market for tickets and merchandise driving royalty payments
Aggregate data from all events on our platform to provide an analytics platform for event organizers 


## Project Goals:

  ### Core Goals:

  - Create Token to be used on platform as currency - “TIX”
  - Create contract in solidity 
  - Create functionality for NFT ticket at point of access
  - QR code to access event
  - Create smart contract to mint “event” tickets
    - Limit supply to event capacity
  - Create smart contract for event attendees to purchase tickets from directly from event creator
    - Royalties to event organizer (artist)
    - Royalties to platform
  - Create smart contract for event attendees to purchase tickets on secondary market (non-owner)
    - Royalties to event organizer (artist)
    - Royalties to platform
  - Use streamlit / javascript to create front end interface


  ### Supplemental Goals:

  - Create front end interface for secondary sales platform
  - Run analytics for revenue projections 
    - Initial ticket mint supply
    - Secondary ticket sales
    - Incentive sales
  - Create smart contract for users to trade NFT merchandise from these events
    - Royalties to event organizer (artist)
    - Royalties to platform 
  - Incentivize users to engage platform
    - Concerts - airdrop clip / song recordings to event attendees
    - Sports - airdrop clip of biggest in game moment
    - Photography/ Recordings from event 
    - Loyalty rewards for holders of native token - Tokenomics
    - Exclusive events 
    - Loyalty rewards for largest collectors of individual artists / teams 
    - Exclusive NFTs


## Back-end Development:

Solidity- v 0.6.0
Metamask
Ganache
Python
Streamlit / Javascript 
QR code generator

### Solidity - New Tools:

AccessControl
provides a general role based access control mechanism. Multiple hierarchical roles can be created and assigned each to multiple accounts
Ownable
is a simpler mechanism with a single owner "role" that can be assigned to a single account. This simpler mechanism can be useful for quick tests but projects with production concerns are likely to outgrow it
Context
While these are generally available via msg.sender and msg.data, they should not be accessed in such a direct manner, since when dealing with meta-transactions the account sending and paying for execution may not be the actual sender (as far as an application is concerned).
This contract is only required for intermediate, library-like contract
Utilities
Counters
a simple way to get a counter that can only be incremented or decremented. Very useful for ID generation, counting contract activity, among other
 
Our initial smart cards utilized a number 
 
However, we needed to 


Frontend Development:



Using strealit to create front end interface
QR Code - to access event
Creating the visual for the NFT tickets






Project Deployment:


This is the working product we have in place for our decentralized ticketing platform with a step by step guide on purchasing event tickets.


Connecting the owner (event organizer) wallet to Metamask




















Connect “Customer Wallet” to interact with the smart contracts / front end interface



Compiling the smart contract and deploying on the ethereum development network

Connecting customer’s wallet (wallet 4) to interact with the deployed smart contract


































## Feasibility Analysis:

The following assumptions were made when conducting this analysis:

Ticketmaster / Stubhub typically add a surcharge of at least 10% on each sale
See citations for this figure 
Estimated cost for running the platform and deploying the smart contracts / initial ticket mint is $250,000
See citations for this 

Based on our assumptions above, here is a rough estimate for the platform’s Net Income for a single large scale (20,000+ event attendees) event. These calculations do not factor in merchandise sales / secondary sales as we do not have these operations functioning yet. With our estimated operating costs our platform would break even after 3 large scale events.




## Additional Development - Project Roadmap:

These are the next features we would focus on building to enhance our platform and continue to add value to the ticket buying experience. 

1. Create front end interface for secondary sales platform
2. Run analytics for revenue projections 
3. Secondary ticket sales
4. Incentive sales
5. Create smart contract for users to trade NFT merchandise from these events
6. Incentivize users to engage platform
7. Launch native token for platform

### User Benefits:

These next set of features would empower the user base through a functioning secondary market (peer to peer sales) and adding loyalty rewards to the user base. These benefits would encourage users to remain engaged on the platform and be a key selling point for new customer acquisition. 

### Event Organizer Benefits:

There are also benefits towards event sponsors / organizers via royalties on secondary NFT sales and NFT merchandise sales. In addition to increasing the revenue for each event through royalties from ticket / merchandising sales we would aggregate the platform’s data to provide an analytics platform for event organizers to project revenues, streamline efficiencies, and provide benchmark metrics to similar events. 

This would likely be deployed through a second front end interface that the event sponsor / organizer would log in to with the wallet they used to deploy the initial smart contract to mint the ticket supply.

 
## Conclusion:

We originally had written much more complex code with a number of the functions we outlined in our future project roadmap. However, we found that linking the complex code with Streamlit was a challenge. 

This led us to making the executive decision to simplify the smart contract and limit the amount of functions within the smart contract to have a working proof of concept for project completion. 

Even with limited functionality we believe our platform has the ability to streamline the current ticketing exchange ecosystem and provide a platform that excites users / organizers to utilize our blockchain platform. 

## Citations:


https://www.youtube.com/watch?v=0i6V2hOosB4

https://dev.to/dabit3/building-scalable-full-stack-apps-on-ethereum-with-polygon-2cfb

https://github.com/Andreasaarrestad/ethereumTicketSystem

https://appinventiv.com/blog/cost-of-nft-marketplace-development/

