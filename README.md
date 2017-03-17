# BUIP ---: Retroactive Code Review by Security Experts

Proposer: Trevin Hofmann

Authors: Trevin Hofmann, ---

Status: Draft

Proposed on: ---

### Summary

This BUIP proposes the allocation of funds to pay for a thorough review of the Bitcoin Unlimited source code. It also outlines the process for requesting and selecting project bids, the expectations and required project deliverables, and the process for disbursing funds to the selected bid(s).

### Rationale

The Bitcoin Unlimited client has suffered two major incidents resulting from flaws in its source code. In January 2017, the Bitcoin.com mining pool unintentionally created a block exceeding 1 MB [1]. This block was expectedly orphaned by the rest of the network, costing the Bitcoin.com mining pool the block reward. In March 2017, a remote crash vulnerability was used by an attacker to bring a large number of Bitcoin Unlimited nodes offline [2].

It is highly plausible that more flaws remain in Bitcoin Unlimited's code. If found and exploited, these flaws could potentially be used by attackers to cause significant damages to Bitcoin Unlimited operators and disrupt the Bitcoin network as a whole. To protect Bitcoin Unlimited operators and the Bitcoin network, it is imperative that the client's source code is thoroughly reviewed by security experts in order to locate and responsibly patch any existing flaws.

### Funding

--- TODO: Describe the funding limits for the project.

### Request for Project Bids

--- TODO: Describe the process for circulating a request for security experts to bid for the code review project.

### Bid Selection

--- TODO: Describe the process for selecting which bid(s) will be accepted.

### Review Expectations and Deliverables

--- TODO: Describe guidelines and expectations for the code review, as well as the required documents to be delivered.

### Disbursement of Funds

--- TODO: Describe the process for disbursing funds to the security researcher(s).

### References

[1] https://bitco.in/forum/threads/buir-2017-01-29-statement-regarding-excessive-block-by-bitcoin-unlimited-software-29-jan-2017.1790/
[2] https://medium.com/@g.andrew.stone/buir-2017-2-23-statement-regarding-network-wide-bitcoin-client-failure-28a59ffffeaa#.u1vuy0lds
