---
layout: post
title:  "Voting and incentives"
date:   2019-08-29 11:00:00 +0700
categories: blockchain
---

Bitcoin in its original form was designed as a Peer-to-Peer system. The decisions on which blocks are the valid part of history can be compared to a vote. The first article on blockchains calls such systems “property clubs” and a “constitutional microdemocracy”[1]. The votes for the correct history however are coupled with incentives. We can consider a game where a group votes on a decision to adopt a policy and those who voted correctly receive a reward (R), and those who voted incorrectly a penalty (P). Consider that participants will want to estimate the potential total reward TR in relation to them being correct (p_c), namely maximise TR = p_c * R — (1-p_c)*P. Traditionally in democracies there is no penalty for not voting. Voting incorrectly is not a notion, since the decision to adopt some change is not true or false (one might imagine it could, although I remain unconvinced about Hanson’s Futarchy).

In Proof-of-Work there is in fact a penalty for not voting on the correct history, namely burning energy and lost block reward. In Proof-of-Stake this issue resurfaces as Nothing-at-Stake problem, because stakeholders can vote on alternative chains without penalty.

In its current design Proof-of-Asset does not have penalties for voting of delegates, but decisions for valid history do have penalties. The Nothing-at-stake problem is solved because delegates can lose the initial investment. One key insight is that incentive to buy the asset directly reflects the expectation of fees to be earned. This allows a competition to form. How voting for delegates themselves should be handled is an open problem. The original design for PoA was a purely market based system. The consensus has to form how many ring-holders i.e. delegates exist. One of the critical insights of a DPOS scheme is that 2 layers can and will exist, and it makes sense to account for that fact from the start. DPOS was invented by the same person who invented PoS [3], so it is a natural extension.

This form of delegation and measurement potentially can apply in a completely general context where participants want to delegate any function to one or more delegates. For example say there is consensus that f(x) should be performed at time t+10. Then the network could issue a delegate contract and pay anyone who performs f(x). As long as it is measurable the network can delegate this call and the reward will be paid.

1. http://nakamotoinstitute.org/secure-property-titles/
2. https://vitalik.ca/general/2018/03/28/plutocracy.html
3. https://bitcointalk.org/index.php?topic=27787.0;all
4. https://bitsharestalk.org/index.php?topic=1138.0