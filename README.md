# Createing a dApp with Arweave + React
## What are we building?
Before we dive in, let's have a quick discussion about what we are trying to achieve.
## A decentralized Twitter
At the end of this guide you will have built a decentralized Twitter-like application deployed permanently on arweave. Because both data and front end are stored on arweave, no third party or bad actor can censor them or take it down. All for the cost of less than a penny!

We're going to assume you already have some familiarity with React and start with a sample app — filling in the Arweave specific functionality to learn how to build directly on Arweave.

Instead of reinventing the wheel we are going to take advantage of existing protocols built using Arweave, the [Public Square protocol](https://gist.github.com/samcamwilliams/811537f0a52b39057af1def9e61756b2) and ArweaveID. Building on top of existing protocols this way is known as composability and it’s a big part of web3. It enables rapid iteration and exploration by building on top of existing building blocks without having to invent from scratch each time.
## Topics
This guide is broken into for sections that take roughly 20-30 minutes to complete depending on your experience. The level of React understanding you should have is the amount taught by the [ReactJs tutorial](https://reactjs.org/tutorial/tutorial.html), if you are unfamiliar with React JS this is a great place to start.
1. [Querying Arweave](01-QueryingArweave.md#querying-arweave) (25-30 minutes)
2. [Integrating Arweave-js](02-IntegratingArweaveJS.md#integrating-arweave-js) (25-30 minutes)
3. [Posting transations](03-PostingTransactions.md#posting-transactions) (15-20 minutes)
4. [Polishing and Deploying]() (25-30 minutes)

