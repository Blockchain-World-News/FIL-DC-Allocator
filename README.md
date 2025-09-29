# Blockchain World News Fil+ DC Allocator  
## V6 FIL+ DC Allocator Bookkeeping Repository
**Conutry of Operation** : Republic of Korea  
**Contact**  
  . e-mail : psh0691@gamil.com  
  . Slack : psh0691  
  . Kakaotalk : 0691psh  
  . Telegram : heavenwish
        
# Allocator Json Link
[Blockchain World News Filecoin Plus DataCap Alloctor](https://github.com/filecoin-project/Allocator-Registry/blob/main/Allocators/recukrpBz5CjxcaHR.json)

# What is Filecoin Plus
The goal of the Filecoin Plus program is to increase the amount of useful data stored with storage providers by clients on the Filecoin network.  

In short, this is achieved by appointing allocators responsible for assigning DataCap tokens to clients that are vetted by the allocator as trusted parties storing useful data. Clients then pay DataCap to storage providers as part of a storage deal, which increases a storage provider’s probability of earning block rewards.  

Filecoin Plus creates demand on the Filecoin network, ensuring the datasets stored on the network are legitimate and useful to either the clients, or a third party.

## DataCap
DataCap is a token paid to storage providers as part of a deal in which the client and the data they are storing is verified by a Filecoin Plus allocator.  
Batches of DataCap are granted to allocators by root-key holders, allocators give DataCap to verified clients, and clients pay DataCap to storage providers as part of a deal.  
The more DataCap a storage provider ends up with, the higher probability they have to earn block rewards.  

**Blockchain World News**, as a Filecoin Plus DataCap Allocator(It used to be called a **notary**), allocates DataCap by verifying data with clients who want to store public data.

# Steps to DataCap as a Client
The steps a client should follow to DataCap are as follows:

1. Create a Filecoin wallet.

2. Choose an allocator.

3. Check that you satisfy the requirements of the allocator. In the case of uploading open source datasets with BWN as the Fil+ Allocator,  
   (1) satisfy a third party Know Your Customer(KYC) identity check,  
   (2) provide the details of storage provider (entity, storage location) where the data is intended to be stored,  
   (3) demonstrate proof that the dataset can be actively retrieved.  

5. Submit an [application](https://github.com/Blockchain-World-News/FIL-DC-Allocator/issues/new/choose) for DataCap from an allocator.

6. Use the DataCap in a storage deal.

# Filecoin Plus Reference Site
There are three resources you can use to check the current status of the Filecoin+ deals and participants:

 - The [Filecoin Pulse dashboard](https://filecoinpulse.pages.dev/allocators/) includes visualizations of and tables for data about Filecoin Plus deals on the Filecoin blockchain, organized by Allocators, Clients, and Storage Providers.  
 - The [Datacap Stats dashboard](https://datacapstats.io) shows DataCap allocations, including the number of allocators, clients, and storage providers. You can also see number and size of deals.  
 - The [Starboard Dashboard](https://dashboard.starboard.ventures/market-deals) includes network health data related to Filecoin Plus verified deals.  


# Diligence Clients

## New User Check
  - Is this a completely new GitHub ID? (less than 2 months old)
  - Is this the first time this GitHub ID has applied for DataCap in this or other allocotor pathways?
  - If yes to either, applicants will have a maximum DataCap allowance for their first application

## Client ID Check (KYC)
 - All applicants will be asked if they are willing to complete a free Know Your Customer (KYC) check to confirm themself as a human user associated with a speicific GitHub ID.
 - If they decline the check, they will be significantly limited in the maximum amount of DataCap they can request unless they are able to provide other forms of client identification.
 - I would use a third party KYC service to confirm the identity of the customer and the organization he represents. I would consider using the ""toggle"" third party tool.
 - The client will need to provide a GitHub account, a slack account.
 - The third party tool ""toggle"" verification may involve face verification and ID verification.
 - We hereby declare that the private information of the customer is only used to verify whether the customer is a real person or not, and will not use the information for other purposes.

# Description of Data Diligence
## 1.Data Sampling
at the time of the client's application, I will ask the client to provide a sample of the data.
Ask the client to describe how they do their data preparation work.
In order to avoid the situation of sector filling, I will use Lotus to download their files according to the CID after each round of DataCap allocation, and randomly check whether the data stored in the SP is consistent with what is declared.

## 2.Verification Tools Used
I would use the following tools:

1. [DataCapStats.io](https://datacapstats.io/)
2. CID Check Bot
3. AC Bot


       
# Detailed Allocator policies
## Minimum client requirements:
 - At least two sealed copies of a dataset, stored with two separate Storage Provider entities, each in different regional locations.
 - The dataset is made readily retrievable (via an unsealed copy) on the network and can be regularly verified (through the use of manual or automated verification that includes retrieving data over the course of the DataCap allocation timeframe).
 - Clients disclose their storage provider partners upfront or designate an approved network tool they will use for SP selection
 - Clients are required to apply for DataCap using the following GitHub repo [LINK](https://github.com/Blockchain-World-News/FIL-DC-Allocator/issues/new/choose) which contains questions related to the client role, data preparation, financing, dataset details, and storage provider distribution plan
   
# DataCap Distribution:  
## First-Time User Allocation:  
    With KYC: Up to 50 TiB.  
    Without KYC: Up to 10 TiB.  
 ## Trusted User Allocation:  
    . 1st allocation: 5%  
    . 2nd allocation: 15%  
    . 3rd allocation: 30%  
    . 4th allocation: 50%  
   Eligible for up to 5 PiB after successful onboarding, with KYC completion.  

  ## Other
  **- Subsequent Allocations**: Triggered when >75% of prior DataCap is used, reviewed within a 3-day SLA.  
  **- DataCap Expiration date**: 3 months, if not used afterwards, the application will be closed and the remaining DCs will be removed.  
  **- Non-Compliance**: Applications closed if clients abandon or fail to complete onboarding; GitHub IDs and miner IDs may be flagged for future exclusion.  
  **- VPN Usage**: Permitted, but clients must ensure actual locations comply with geographic policies; location spoofing is prohibited.  

    
## Dispute / Appeals
- For any disputes between our allocator and a client, hereby termed appeal(s), we will source the appeals through the Open Data Allocator Appeals Form (https://docs.google.com/forms/d/e/1FAIpQLSfkdb_p9sg5sx_bnSlX0r9rdKXFGmz4dGC1cBtMEYuDym3Ecw/viewform) where all our clients can submit an appeal and someone on the allocator team will address it with a 14 day SLA. 
- We would like to respect the privacy of the client and do not plan to host a public resolution process.
- For disputes raised by community members/non-clients about our allocation approach and strategy, we will comply with the public dispute tracker that is being built by the Filecoin Foundation Governance team. We can commit an SLA for such disputes to be 21 days.
