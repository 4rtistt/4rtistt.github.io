---
layout: post
title: "Introduction to Zero Knowledge Proofs"
categories: ZKP learning
permalink: introduction-to-zkp
author: f4tu
meta: "Introduction to Zero Knowledge Proofs"
tags: ZKP Cryptography
---

Get basic knowledge about zero-knowledge proofs, which are a way to prove a statement is true without revealing anything beyond the truthiness of the statement.

### Introduction

As described abose, ZKPs are a way to prove a statement is true without revealing anything beyond the truthiness of the statement. It means like "I could prove you that know the fact without tell you a fact".

- I know value `X` such that `SHA256(x) = 0x7ace...` but don't tell you `X`.
- I know how to fill a map with three colors so that every two adjacent regions have different colors.
- ...

#### Example
##### Digital signature

In Ethereum, all transactions are signed with public-key cryptography. Every account have a key-pair (public key and private key). You can not join the transaction without knowing private key.