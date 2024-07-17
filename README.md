# Blockchain-based Voter Registration System
This project implements the technology for a blockchain voting system in Python, with the intention of increased voter turnout and security.


## Motivations and Background
Voting systems have not been digitized for fears of hacking, verifiability and trust.
With the current paper ballot system, we have concerns of:
- inefficiencies
- low turnout
- voter disenfranchisement
- socioeconomic barriers

We propose that a blockchain system should be tested to monitor for improvements in these areas.

![Our Blockchain Voting System Diagram](https://github.com/madison-nicole/blockchain-based-voter-registration/blob/main/Blockchain%20Voting%20Diagram.png)


## Implementation Details
- This system was built using Python and Flask.
- Transactions are stored as JSON objects (Driver’s license/state ID #, SSN, DoB, Home Address, Email Address).
- We utilized Python’s SHA-256 hashing function.
- We used the Flask interface for testing and UI.


## Potential Concerns with Blockchain Voting
- Electronic attacks are incredibly scalable, such that the cost of breaching of one vote is practically the same as breaching thousands of votes.
- Fixing security issues in a decentralized system is much more difficult than in a centralized system; thus, blockchains can be vulnerable for long periods of time.
- Blockchain is a relatively new and underdeveloped technology, which might cause skepticism among voters.


## Resources on Blockchain Voting
- [Digital Voting with the use of Blockchain Technology](https://www.economist.com/sites/default/files/plymouth.pdf)

- [Decentralized Electronic Voting System Based on Blockchain Technology Developing Principals](http://ceur-ws.org/Vol-2608/paper17.pdf)

- [Going from Bad to Worse: From Internet Voting to Blockchain Voting](https://people.csail.mit.edu/rivest/pubs/PSNR20.pdf)

- [Are Blockchains the Answer for Secure Elections?](https://www.scientificamerican.com/article/are-blockchains-the-answer-for-secure-elections-probably-not/)

<!-- tutorial resource: https://developer.ibm.com/technologies/blockchain/tutorials/develop-a-blockchain-application-from-scratch-in-python/ -->
