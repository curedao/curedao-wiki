---
title: The Decentralized FDA
description: A platonic ideal for the regulation of food and drugs.
published: true
date: 2022-11-17T19:19:40.430Z
tags: dfda, fda, regulation
editor: markdown
dateCreated: 2022-11-04T23:10:39.282Z
---

# Mandate
Maximize average healthy human lifespan by identifying  discovering and disseminating the effects of every food, additive, supplement, and medical intervention while minimizing costs to consumers.

![dfda-overview-purple.png](/dfda-overview-purple.png)

# Overview
The Decentralized FDA is meant to act as a regulatory template or platonic ideal based on crowdsourced best practices for food and drug regulation and compliance. It is meant to be forked, modified where needed, and implemented in various micro-nations, network states, or special economic zones.  

Additionally, the dFDA is NOT a single entity.  It is a protocol or blueprint for an incentivization ecosystem that facilitates a free market for innovation by the countless individuals and organizations needed to realize the precise and personalized medicine of the future.

# Hypotheses

1. Given a clear and optimized mandate, the crowd wisdom of a large body of medical experts can produce policies that are more effective at extending healthy human lifespan than the current regulatory framework.
2. It is possible to implement such a regulatory body in a micro-state or economic zone such as Prospera, a semi-autonomous jurisdiction in Honduras.
3. Evidence of the success of this model will make it possible to promote adoption by other micro-nations.
4. Evidence of the success of this model will make it possible to promote adoption by increasingly larger states.

# Functions and Components
1. **Comparative Policy Analysis** - Aggregate existing approval and certification data from existing national regulatory bodies
2. **Food and Drug Outcome Labels** - Aggregate and analyze real-world data (RWD) to create Outcome Labels subject to Futarchical-weighted review by the board members of the dFDA
3. **Publish Meta-Analyses** - Generate meta-analyses from all completed studies at ClinicalTrials.gov
4. **DeSci Exchange** - A free market for personal data in the form of an embeddable SDK with a configurable transaction fee for the apps embedding it. 
5. **Human File System Protocol and SDK** - A standard protocol for personal data exchange between studies, apps and devices. 
6. **Digital Twin Safe** - A tool for self-sovereign storage of personal data that enables effortless data sharing with clinical safety and efficacy studies.
7. **Certification of Intervention Manufacturers/Sources** via a Decentralized Web of Trust derived from end-user data and reviews traced back though an NFT-tracked supply chain
8. **Intervention Ranking** - Elevate the most promising yet little/known or researched treatments
9. **Decentralized Clinical Trials** - Not only would this increase knowledge but also access and availability of new and innovated treatments to those who need them urgently.

# Objective:  Accelerate Clinical Discovery

- Elevate the most promising yet little known/researched treatments
- Issue certifications for the Decentralized Science web-of-trust
- Provide an API for building trustworthy alternatives to conventional health markets

# Components

## Outcome Labels

Ultimately, the most useful output of a decentralized FDA would be **Outcomes Label** that list the degree to which the product is likely to improve or worsen specific health outcomes or symptoms.

![outcome-labels-plugin.png](/assets/outcome-labels.PNG)

## Data Storage and Sharing

![human-file-system-banner-logo](https://user-images.githubusercontent.com/2808553/180306571-ac9cc741-6f34-4059-a814-6f8a72ed8322.png)

Import data from all your apps and wearables, so you can centrally own, control, and share all your digital exhaust.

Available on the Polygon chain at [humanfs.io](https://humanfs.io) and on [GitHub](https://github.com/curedao/digital-twin-safe). 

Based on the awesome [Gnosis Safe](https://gnosis-safe.io/), the most trusted platform to store digital assets.


## The Human File System Protocol SDK

**A Simple API for Patient-Controlled Health Data Aggregation, Sharing, and Monetization**

A set of interoperable software libraries that can be used independently to create user-access controlled digital twins on the blockchain.

The libraries can be used independently, but will all be included in the HumanFS SDK.

### The Need for a Human File System Protocol

There are 350k health apps containing various types of symptom and factor data.  However, the isolated data's relatively useless in all these silos. In order to make clinical discoveries, all the factor data needs to be combined with the outcome data.

**Web2 Problem**

The web2 solution to combining all this data is a nightmare of

1. creating thousands of OAuth2 data connectors
2. running a bunch of importer cron jobs on AWS.

**Web3 Solution**

User auth/databases/key management/access control/3rd party OAuth tokens abstracted away by a single, easy-to-use API

i.e.

Pain Tracking App A:

`db.collections.create('Arthritis Severity', timeSeriesData);`

Diet-Tracking App B:

`let timeSeriesData = db.collections.get('Arthritis Severity');`

⇒ Making it possible for Diet-Tracking App B (and/or Pain Tracking App A) to easily analyze the relationship between dietary factors and Arthritis Severity using causal inference predictive model control recurrent neural networks.

## Digital Twin Safe

Import data from all your apps and wearables so you can centrally own, control, and share all your digital exhaust.

![digital-twin-safe-screenshot-home](https://user-images.githubusercontent.com/2808553/200402565-72bc85a3-deb2-4f1a-a9b1-bde108e63d87.png)

## Variables

![digital-twin-safe-screenshot-variables](https://user-images.githubusercontent.com/2808553/200402422-41213d62-324d-44db-a725-fc0eab619e45.png)

### Data Sources

![digital-twin-safe-screenshot-data-sources](https://user-images.githubusercontent.com/2808553/200402625-8c4ab0b1-829c-4128-8b12-509c2f885b96.png)

### 📚 Libraries Used

Data Storage, Authorization and Sharing - Lit Programmable Key Pairs (PKPs) for access control over protected health information (PHI) with data storage on Ceramic. XMTP (Extensible Message Transport Protocol) is an open protocol and network for secure, private messaging between patients and physicians.

## Incentivizing Data Sharing

![desci-exchange-text-logo-wide-text-hands-background.png](/desci-exchange-text-logo-wide-text-hands-background.png)

![desci-exchange-how-it-works.png](/desci-exchange-how-it-works.png)

## Architecture Overview

![desci-exchange-diagram.svg](/desci-exchange-diagram.svg)

## Digital Twin Skeleton Key NFT

![digital-twin-nft.png](/digital-twin-nft.png)

Possession is checked when accessing your Digital Twin Safe.
If you don't have the key, you're prompted to mint one.

The Digital Twin Skeleton Key NFT is a soul-bound NFT that can only be minted if you do not already have one.

This key gives you the ability to mint Data Gem Data Access NFTs using your imported data.

## Life Force Score

The attached avatar image and Life Force Score metadata are updated daily based on their imported data performing
healthy activities, such as having a good sleep schedule, hydrating, and exercising.

This metadata is available to various metaverse game ecosystems and can influence their scores and abilities in these
games.

# Data Gems

![data-gems.png](/data-gems.png)

Data Gems bestow their holder with magical powers enabling them to transcend the physical world and see an aspect of its inter-dimensionally linked digital twin.

A more boring way to put it, is to say that Data Gems are NFT tokens that give the holder the ability to decrypt a data stream.

They can be mined by the data owner and can be given or sold to other Analog Twins or businesses.

# Benefits

## For Individuals

- eBay for health data - You can earn magic internet money by selling your data regarding symptoms, treatments, and
  factors to pharmaceutical companies, insurance companies, and other data buyers
- Control access and use of your data through fine-grained permissions
- Continuously monitor and audit the data you provide to other organizations

## For Health Apps

- Connected real-world data yields better insights for your users
- Apps that embed the exchange in their app earn a 0.5% transaction fee for each data sale
- Connect to third-party sources to enrich your data, or easily connect to a user's existing data

## For Pharmaceutical Companies

- Conduct long-term safety and effectiveness studies by linking their clinical trial data to medical claims and
  electronic health record data
- Refine models for finding rare disease patients by linking diagnostic lab, genomic, and imaging data
- Discover new therapeutic candidates with connected data

## For Insurers

- Improve value-based care analytics and sharpen total cost of care estimates by linking to EHR and clinical data
- Connect to the nation's largest ecosystem of health data
- Hone risk adjustment factor calculations by linking claims to social determinant's data, to properly estimate the true
  cost of patient care


# Continuous Improvement
Key Performance Indicators (KPIs) should be monitored in the jurisdictions where each fork is applied.  This will allow for A/B testing of the outcomes of particular policies and statutes that differ among forks.  

# Governance
The policies of dFDA can be submitted and ratified using a Futarchical Voting mechanism whereby votes are weighted based on the voter's historical record of voting on proposals linked to improvements in outcome KPIs.

DeSci doesn't seem to give a much greater focus on collaboration rather than profits, which, we initially hoped would be the case.
Thus, progress has been much slower than first anticipated.
Creating a decentralized FDA as a government entity to function as the new backbone of research could be a critical way to ensure that we achieve this and finally see the exponential progress needed to ensure everlasting health for all.

A board of directors would be useful to ensure the credibility of the organization needed.
To ensure that micronations and, hopefully, eventually, greater nations would start using the organizational structure, it would be critical to get as much credibility as possible.
We propose creating a board of 8-10 people to help accomplish that objective.
AGI is slowly but surely being developed to have brain power far greater than what is seen in any human being and, thus, we propose having Norn (https://norn.ai/) as part of the board to help ensure the much-needed cognitive ability of the project.

## Benefits to Board Members
 - Elevated on-chain reputation for prediction accuracy
 - Gains from futures market
 

# Proposed Implemenations

## A Futures Market for Crowdsourcing Net Value of Interventions

QALY stands for Quality Adjusted Life Year. The QALY is commonly used in health economic evaluations as a means of quantifying the health effect of a medical intervention.
 
### The Calculation
The QALY can be calculated using the following formula which assumes a utility value (quality of life) between 
- 1 = perfect health and 
- 0 = dead

QALYs = Years of Life x Utility Value
 
This means:

If a person lives in perfect health for one year, that person will have 1 QALY.
(1 Year of Life × 1 Utility Value = 1 QALY)
 
If a person lives in perfect health but only for half a year, that person will have 0.5 QALYs.
(0.5 Years of Life x 1 Utility Value = 0.5 QALYs)
 
Conversely, if a person lives for 1 year in a situation with 0.5 utility (half of perfect health), that person will also have 0.5 QALYs.
(1 Year of Life x 0.5 Utility Value = 0.5 QALYs)
 
The QALY is used to quantify the effectiveness of a new medicine versus the current one. In other words, the current standard of care is taken as the baseline, and the QALYs gained from the new (improved) intervention are counted in addition.
 

## Crowdsourcing QALY Estimates

Numerous studies have illustrated the ability of the combined estimates of a large number of minds to produce more accurate predictions than even the greatest experts in the group. However, there are five components necessary to produce optimal results:

1. Independence - Opinions of people are not determined by the people around them.
2. Decentralization - People can draw on domestic knowledge and specialize in it.
3. Opinion Diversity - Everyone must have private information, even eccentric explanations of famous facts. 
4. Trust - Every person trusts that a group can make a fair decision.
5. Aggregation- To turn private judgments into a mutual decision, you have to follow a mechanism.    
By applying these elements to a futures market that estimates the change in utility value and average lifespan, it's possible to acheive a far more accurate cost-benefit analysis of interventions than is currently possible with small centralized regulatory bodies. 

## A Futarchy-Based Meritocratic Regulatory Framework

Medical experts will receive soul-bound non-transferable deFDA Credential NFTs (FDA-CRED) will be issued to all members of the American Medical Association (AMA) and other international bodies which verify medical credentialing.

One deFDA fungible Reputation Token (FDA-REP) will be airdropped to holder of FDA-NFTs for each intervention that is proposed for a specified population.

Medical experts can stake their token in one of three pools based on their belief for the experimental population relative to a control group not exposed to the intervention:

1. "Uncertain Pool" - they are uncertain of the outcome of the reform
2. "Harmful Pool" - reform will result in a relative net average DECREASE in healthspan
3. "Helpful Pool" - reform will result in a relative net average INCREASE in healthspan

If they do nothing, it will be assumed that they did not review the proposal.

If the "Helpful Pool" is the majority, the proposal will be approved and implemented. Post-marketing pharmacovigilance data will be collected from the participants and used to determine the relative change in healthspan between affected and unaffected populations.


# Roadmap

1.  Contract Research Organization: Perform research for DAOs and corporations alike. Focus on early stage and replication experiments. Trials run out of Prospera or in a decentralized manner.

2. Certifying Agency: 
	- Certify safety and efficacy ratings; using a gradient rather than simple pass or fail.  
	- Approve proposed experiments (Institutional Review Board).
	- Certify named and pseudonymous participants in DeSci/Biomedicine, allowing a web-of-trust to develop.
	
3. Regulatory Agency:
	- Provide a Web3 API for marketplaces
	- Certify producers, distributors, and recipients of treatments 
	- Build a knowledge graph from 'confirmed' treatment recipients 
	- Certifications for 'bad actors' may be revoked
    
    
# Possible Legal Structures

*'Co' is intentionally ambiguous; may refer to a cooperative, a collective, and a company.*

- Cooperative to own the health data collectively; pool with other aligned organizations to create a massive data set owned by the participants 
- Non-profit to issue certifications and publish code/standards (limited liability through Wyoming non-profit)
- For profit(s) to run experiments and collaborate with other corporations to commercialize therapeutics when feasible
