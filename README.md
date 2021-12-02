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
## Architecture
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
## Gamification
## Summary
## Conclusion
