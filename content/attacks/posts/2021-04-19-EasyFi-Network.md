---
date: 2021-04-19
categories: DeFi
title: "EasyFi Network Hack: $81 Million Stolen Through Mnemonic Key Compromise"
---

## Summary

On April 19, 2021, EasyFi, the Polygon Network-based DeFi protocol, was hacked, resulting in the theft of 2.98 million EASY tokens and about $6 million in USD, DAI and USDT. The total value of the stolen assets was about [$81 million](https://www.halborn.com/blog/post/explained-the-easyfi-hack-april-2021). The attacker [successfully](https://medium.com/easify-network/easyfi-security-incident-pre-post-mortem-33f2942016e9) compromised the mnemonic keys associated with the EasyFi project and exploited them to drain liquidity from the protocol.

## Attackers

The identity of the attackers behind the EasyFi hack remains unknown.

## Losses

The EasyFi hack resulted in financial losses, with the attackers stealing 2.98 million EASY tokens and approximately [$6 million](https://medium.com/easify-network/easyfi-security-incident-pre-post-mortem-33f2942016e9) in USD, DAI, and USDT. The stolen funds were transferred to the address [0x83a2EB63B6Cc296529468Afa85DbDe4A469d8B37](https://etherscan.io/address/0x83a2EB63B6Cc296529468Afa85DbDe4A469d8B37).

## Timeline

- **April 19, 2021 (10:40:26 AM +UTC):** Unusual large transfers of EASY tokens from EasyFi official wallets to unknown wallets on the Ethereum and Polygon networks were detected. This raised concerns about a possible compromise of admin keys or mnemonic keys associated with the EasyFi project.
- **April 19, 2021:** The hacker managed to get access to admin keys and remove existing liquidity to the tune of $6 million from protocol pools in USD / DAI / USDT and transfer 2.98 Million EASY tokens to this wallet address: 0x83a2EB63B6Cc296529468Afa85DbDe4A469d8B37.
- **April 20, 2021 (11:21 AM):** [Ankitt Gaur](https://twitter.com/AnkittGaur/status/1384253351492087819), the founder of EasyFi made a public announcement on Twitter regarding the unauthorized token transfers and addressed an open letter to the hackers. He also reported that his computer was compromised and metamask was altered from the disk.
In the open letter, Ankitt Gaur urged the hackers to return the stolen funds to the EasyFi community. He proposed the possibility of a clean payout of $1 million to a white hacker as a bounty, in order to avoid potential legal consequences.
-**April 23, 2021:** EasyFi Network [announced](https://medium.com/easify-network/easyfi-security-incident-66c02a277a91) HardFork & Tokenswap. Team EasyFi has made the decision to create a new token contract called EASY V2. This decision comes after consultations with exchanges, forensic agencies, stakeholders, and partners. As a result, the EasyFi token ticker will be changed from $EASY to $EZ following a hard fork. This change will apply to addresses holding EASY on the Polygon, Ethereum, and Binance Smart Chain networks, and they will be credited with the new EASY V2 token accordingly.

- **May 7, 2021:** [Interim Compensation plan](https://medium.com/easify-network/interim-compensation-plan-8fa81e46ada4) 
EasyFi has introduced a compensation plan for users affected by the hack. They will receive 100% of their net balances, with 25% compensated immediately and the remaining 75% provided as EZ IOUs. These IOUs are backed by EZ tokens and offer benefits, including participation in incentivization programs with EasyFi and partner projects.

## Security Failure Causes

- **Mnemonic Key Compromise:** The EasyFi hack was the result of a compromise of the mnemonic keys associated with the project. The attacker gained unauthorized access to the mnemonic phrase/admin keys stored in the Metamask wallet, which allowed them to manipulate transactions and drain liquidity from the protocol.

- **Remote Access Exploitation:** It is suspected that the hacker used a previously established remote access method to compromise the physical machine used for official transfers. The attack was executed [remotely](https://medium.com/easify-network/easyfi-security-incident-pre-post-mortem-33f2942016e9), without tampering with the machine itself.

- **Insufficient Security Measures:** The security failure can be attributed to a combination of factors, including inadequate protection of mnemonic keys, potential vulnerabilities in the Metamask wallet, and a lack of strict access controls. These weaknesses provided an opportunity for the attackers to exploit the system and carry out the hack.
