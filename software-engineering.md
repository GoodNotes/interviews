GoodNotes - Example of Technical Challenge - Deprecated

We're using a new challenge, please contact us on careers@goodnotes.com if you want to take it! Don't submit this one, it is just an example of the kind of challenge you would have to face in our interview process.

===
This is an introductory coding challenge to evaluate candidates interested in joining the team at GoodNotes. It is meant to be fun and short (<2 hrs typically) and introduce some of the engineering challenges at GoodNotes.

### Introduction

Conflict Free Replicated Data Types (CRDTs) are data structures that power real time collaborative applications in distributed systems. CRDTs can be replicated across systems, they can be updated independently and concurrently without coordination between the replicas, and it is always mathematically possible to resolve inconsistencies which might result.

#### Recommended Reading
- https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type
- https://github.com/pfrazee/crdt_notes
- https://hal.inria.fr/inria-00555588/PDF/techreport.pdf

### Deliverable
**Study [LWW-Element-Set](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type#LWW-Element-Set_(Last-Write-Wins-Element-Set)) and implement a state-based LWW-Element-Dictionary with test cases.** 

Similar to LWW-Element-Set, the dictionary variant you are going to implement will store a timestamp for each key-value pair. In addition to the add and remove operations, the dictionary variant will also allow updating the value of a key. There should be a function to _merge_ two dictionaries. Test cases should be clearly written and document what aspect of CRDT they test. We recommend you to spend **no more than 4 hours** on this challenge. The provided readings should be sufficient to understand LWW-Element-Set and CRDT on a high level. You are welcome to dig deeper on those but we expect you to come up with the implementation yourself without any help from other open sourced implementations. 

### Grading & Submission
You'll be graded based on code quality and test coverage, and **you can use any language of choice**. 
