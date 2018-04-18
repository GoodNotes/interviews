GoodNotes - First Technical Challenge
===
This is an introductory coding challenge to evaluate candidates interested in joining the team at GoodNotes. It is meant to be fun and short (<2 hrs) and introduce some of the engineering challenges at GoodNotes.

### Introduction

Conflict Free Replicated Data Types (CRDTs) are data structures that power real time collaborative applications in distributed systems. CRDTs can be replicated across systems, they can be updated independently and concurrently without coordination between the replicas, and it is always mathematically possible to resolve inconsistencies which might result.

#### Recommended Reading
- https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type
- https://github.com/pfrazee/crdt_notes
- https://hal.inria.fr/inria-00555588/PDF/techreport.pdf

### Deliverable
**Implement a [LWW-Element-Set](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type#LWW-Element-Set_(Last-Write-Wins-Element-Set)) CRDT with test cases.** 

It may be helpful to start your [reading here with sets](https://github.com/pfrazee/crdt_notes#sets). Test cases should be clearly written and document what aspect of CRDT they test. This challenge should take **no more than 2 hours**. If you take inspiration from other open source implementations of CRDTs, please attribute them properly by commenting which parts were inspired and linking to the original source.

### Grading & Submission
You'll be graded based on code quality and test coverage, and **you can use any language of choice**. Please email us a link to your repository on either [GitHub](https://github.com/gninterview) or [BitBucket](https://bitbucket.com/gninterview). If it's a private repository, pleaes share it to user `gninterview` on either GitHub or BitBucket.
