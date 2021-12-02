___
# Utilizing BitBadges for Gamified Learning Experiences 
> **By Andrew M. K. Nassif**
___

#### Table of Contents
1. [Abstract](#abstract)
2. [Introdution](#introduction)
3. [Architecture](#architecture)
4. [Database](#database)
5. [Game Theory](#game-theory)
6. [Gamification](#gamification)
7. [Summary](#summary)
8. [Conclusion](#conclusion)

## Abstract
BitBadges is establishing a blockchain standard that can be utilized in the creation of gamified learning experiences. Gamified learning experiences can be tailored towards 

## Introduction
BitBadges is an emerging blockchain standard. This document is in relation to what it wants to do with gamified learning experiences and the Digital Learning Challenge (XPrize). 

## Architecture
BitBadges 2.0 is an improvement over BitBadges 1.0. 

## Database
```javascript
{
    attributes: string, //valid JSON object string; not currently implemented
    backgroundColor: string, //Valid HTML color name or hex string
    category: string, //not currently implemented
    collectionId: string, //not currently implemented
    dateCreated: Number, //number of milliseconds since UNIX epoch
    description: string,
    externalUrl: string, //must be in valid URL format
    id: string,
    imageUrl: string, //please use permanent image storage solutions; badges are permanent
    isVisible: boolean, //currently always set to true
    issuer: string, 
    issuerChain: string,
    recipients: string array,
    recipientsChains: string array,
    title: string, 
    validDateEnd: Number, //number of milliseconds since UNIX epoch
    validDateStart: Number, //number of milliseconds since UNIX epoch
    validDates: boolean //true if badge has start/end dates, false if valid forever
}
```

## Game Theory
There are many implications in regards to game theory and how badges will be used to establish different models. Many things will be centered around Social Physics. What that means, is that

## Gamification
## Summary
## Conclusion
