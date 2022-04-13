# What is SimpleNodes?
**SimpleNodes** is a simple decentralized peer to peer framework that uses **simple cryptography functionalities** which aims to help
solving data signing, data availability and integrity issues.

## SimpleNodes Description
Simple nodes consists of 3 different sub directories named data signing, data availability, data integrity.

## What it's not
It's not a technology that **helps users to create or to manage their private/secret keys.**

Technically speaking, decentralized technology may have a way to help users to create or to manage their
private/secret keys but here's my reasons/concerns as to why I don't want to do that.

**Reasons/Concerns**
1. The DKG (https://medium.com/toruslabs/what-distributed-key-generation-is-866adc79620) protocol describes the creation of
master keys or master keypair. If the nodes can create a master keypair or master key then gives to users or use it themselves,
isn't it literally the same as any centralized key management system or cloud encryption/cloud's key generation?
2. The DKG protocol is an advanced cryptography protocol in which i couldn't fully understand it at current moment.
3. If the DKG protocol is able to create a master key or keypair then send to users, how would each of the nodes that has
the DKG keypair respectively manage and store their private keys? In such case, if users want to request the decentralized
technology that uses DKG, can the nodes that uses DKG still able to produce the exact same master key or master keypair
that enables users to login to passwordless system that uses public key authentication?

**Note**\
My current knowledge on DKG is severely limited, as long as the reasons and concerns are still there, I won't be creating
frameworks that uses DKG.
