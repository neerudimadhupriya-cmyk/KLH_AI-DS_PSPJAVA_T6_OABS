# PROJECT TITLE : **ONLINE AUTION AND BIDDING SYSTEM**
**TEAM NO**: KLH/PSPJ/S14/T6
**TEAM MEMBER NAMES WITH ID NUMBERS**:
1. 2620080072 - Madhu priya
2. 2620030223 - Tanshika sai
** SUPERVISOR NAME** : Dr.Madhavi karamudi
**ABSTRACT** :
The Online Auction & Bidding System is a Java-based console application designed to simulate a timed online auction process. The system allows users to list auction lots with starting prices, minimum bid increments, and closing times, while bidders can place valid bids and set secret maximum limits through proxy bidding. It automatically validates bids, resolves competing proxy bids, determines winners and final prices, and handles closed or unsold lots. The project is developed progressively alongside the Java course, beginning with basic console operations, conditions, loops, methods, arrays, and gradually extending to object-oriented programming, interfaces, custom exceptions, records, file handling, collections, priority queues, maps, comparators, and streams. Auction data, bids, and settlement results are persisted to files, allowing the system to reload and resolve overdue auctions. The project demonstrates how fundamental Java concepts can be applied to build a complete real-world system.
**PROJECT STRUCTURE: **
Online-Auction-Bidding-System/
│
├── README.md
│
├── src/
│   ├── Main.java
│   ├── AuctionHouse.java
│   ├── Lot.java
│   ├── Bidder.java
│   ├── Bid.java
│   ├── BidValidator.java
│   ├── InvalidBidException.java
│   ├── AuctionClosedException.java
│   └── SettlementResult.java
│
├── data/
│   ├── lots.txt
│   ├── bids.txt
│   └── settlements.txt
│
└── reports/
    └── auction-report.txt

**EXECUTION INSTRUCTIONS** :
Ohh, if you're going to run it using **Notepad + Command Prompt**, write the execution instructions like this:

**Execution Instructions:**

1. Open the `.java` file in Notepad and save it with the `.java` extension.
2. Open Command Prompt, navigate to the folder containing the file, and compile it using `javac Main.java`.
3. Run the program using `java Main` and follow the instructions displayed in the console.

** GIT COMMANDS:**
git init
git add .
git commit -m "Initial project setup"
git branch -M main
git remote add origin <repository-url>
git push -u origin main
   

