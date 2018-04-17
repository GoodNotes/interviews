# GoodNotes Backend Technical Challenge

### Introduction
This is a take-home coding challenge to evaluate candidates interested in joining the backend team at GoodNotes. 

## Deliverables

### Part 0: LWW-Element-Set CRDT
You should have completed in the [first technical challenge](https://github.com/GoodNotes/interviews/blob/master/first_challenge.md).

### Part 1: LWW-Element-Set Server
Build a Restful API to create new LWW-Element-Sets and add/remove elements from a LWW-Element-Set. Attach a database to make the data persistent.

### Part 2: Chaos Monkeys

A Chaos Monkey is a bot that sends actions to the server that mimic user behaviors.

**Implement and deploy the following Chaos Monkeys:**

1. **Normal** - This Chaos Monkey adds and remove elements from LWW-Element-Sets at random intervals.
2. **Offline-to-Online Sync** - This Chaos Monkey mimics a user who adds and removes elements to a set offline, and then goes online expecting their sets to sync up.
3. **Client Viewer** - This Chaos Monkey views a set by merging the server's set into their own local copy of LWW-Element-Set, and also expects to view updates to the set in near real-time.

### Part 3: Deployment

Build a **clean deployment flow** for LWW-Element-Set server and chaos monkeys for both development and production environments.

### Part 4: Scale

**How would you ensure the server can support 1 million concurrent chaos monkeys?**

Answer this question in the `README.md` file of your repository.

Take the time to go into detail as your answer here is important to us. Use this question as a spring board to talk about real world scaling challenges and solutions and what part of the codebase to optimize or upgrade. 

## Grading & Submission
It's suggested to allocate equal amounts of time to each part. If the assessment is taking too long, you can stop after 8 hours and write down a TODO list of unfinished items and we will still look at the assessment favorably. 

When evaluating, we are focusing on code quality, communication of decision making, and deployment practices within your code, and scaling experience with your answer. For this assessment, deploying on the production platform you're familiar with (AWS, Google Cloud, etc) is preferred over deploying to Heroku in order to display your deployment experience.

Please email us a link to your repository on either [GitHub](github.com/gninterview) or [BitBucket](bitbucket.com/gninterview). If it's a private repository, pleaes share it to user `gninterview` on either GitHub or BitBucket.
