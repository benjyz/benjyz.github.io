---
layout: post
title:  "Blockchains and decision making processes"
date:   2019-09-10 10:00:00 +0700
categories: blockchain
---

There has been a recent uptick on a general blockchain governance debate, see [1] — [6]. I wanted to collect some links and add some thoughts from my own research in this area.
One can consider goverance as a subset of problems related to collective decision making. An initially helpful assumption from mechanism design (see [9]) is that the protocol designer and the participants are different parties. A fully Peer-to-Peer system would assume that all participants fully engage in the entire process (peers are decision makers). However, with growth of blockchains this is no longer valid. The number of people working on code and/or making decisions (ND) is very small compared to the number of users (NU). As the ratio of ND/NU grows smaller (say from 1% to 0.0001%), the power of developers or generally decision makers grows. [6] provides an interesting overview over the history of the development dynamics in Bitcoin.

To focus on some more formal method of analysing a group decision making process I want to assume that there is a set of participants (P), and all members of P have equal power (one CPU — one vote). Say the set of P is small and coordination among members is cheap. If some member M of P were to propose a change C to the protocol, what could an idealised process look like? We first could assume that the proposed change is fully formulated and ready to be merged. The natural method would be a vote among the remaining set (P — M), similar to a vote of representatives in a parliament. Likely there would be many additional processes when changes can be proposed, in what frequency, in what format, etc. Note changes to code and any other decisions (what blocks are valid), are here formalised as simply decisions points. Much of the current confusion comes from the fact that changes to code and deployment of code is not or badly formalised. Hardforks assume that decision makers are somehow identifiable for polling or coordination. For the role of constitutional changes see the first article on blockchains [10].
The problem of governance is related to and increases at scale. As the set of P grows there is going to be a growing long tail of participants with little power. The informal processes of a set of peers is no longer sufficient, if there is going to be a big fraction of participants who have little or no power. In the case of voting this introduces a paradox which has been formally analysed as early as 1793: “in single-stage elections, where there are a great many voters, each voter’s influence is very small. It is therefore possible that the citizens will not be sufficiently interested [to vote]” [7].

Governance/decision making in Proof-of-Stake systems is very different from decision making in Proof-of-Work systems (with good and bad consequences). The reason being that stakeholders can be potentially identified. Say we have a set of participants P with one big stake holders (B) and N smaller stake holders, with B not having the majority stake, but sufficiently close to a majority stake. The smaller stakeholders might be aware of the real world identify of B and lobby him to make certain decisions. B might choose to reveal his identity to only some small stake holders or other such schemes. In Proof-of-Work these coalition forming processes exist, but they are much less pronounced and explicit.
There seems to exist the position that “cryptocurrency is apolitical money” and all decisions come down to technical decisions. If it is agreed that the vast majority of users is not capable or interested in making a decision, there is still the question how experts should be “elected”. If developers come to their position merely by happenstance and decisions of existing developers, this is the position of “informal opensource governance is sufficient”. However, economic and social beliefs and how they inform decisions by no means follows technical logic alone. I want to highlight the importance of game theory, mechanism design, social choice theory, legal theory, etc. and that a technical/social distinction at the expense of those topics is not helpful.

Do we have any precedent for such decision making processes on a global scale? The Internet itself has a history and can be studied [8], next to the history of law and social organisation. However, I’m currently more interested in formal models of voting and incentives, also as they related to PoW/PoS/DPoS and alternative systems.

* [1] https://medium.com/@bytemaster/the-limits-of-crypto-economic-governance-9362b8d1d5aa
* [2] https://vitalik.ca/general/2018/03/28/plutocracy.html
* [3] https://medium.com/@FEhrsam/blockchain-governance-programming-our-future-c3bfe30f2d74
* [4] https://medium.com/@Vlad_Zamfir/against-on-chain-governance-a4ceacd040ca
* [5] https://stokes.io/post/governance-is-the-elephant-in-the-room
* [6] https://blog.companyzero.com/2015/11/bitcoins-biggest-challenges
* [7] https://en.wikipedia.org/wiki/Paradox_of_voting
* [8] https://en.wikipedia.org/wiki/Internet_governance
* [9] http://www.cs.yale.edu/homes/jf/nisan-ronen.pdf
* [10] http://nakamotoinstitute.org/secure-property-titles/