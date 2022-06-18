# QUESTmissions

# Ch 1 Day 1

Explain what the Blockchain is in your own words.
  The Blockchain is a digital decentralized storage database that is stored in blocks and chained to gether after each block is full. The data is stored     among computer network nodes.

Explain what a Smart Contract is.
  A Smart Contract is a set of peramiters created execute a task and record the outcome on the blockchain.

Explain the difference between a script and a transaction.
  Transactions are executed to make a change to the data on a blockchain and a script is how this transaction can be viewed on the blockchain. 
  
 # Ch 1 Day 2
  
 What are the 5 Cadence Programming Language Pillars?
 
  Safety and Security, Clarity, Approachability, Developer Experience, Resource Oriented Programming
 
 In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful (you don't have to answer this for #5)?
 
  Safety and Security provides builders and users with confidence in the technology they are interacting with, Clarity allows for seamless adoption, Approachability provides familiarity, and Developer Experience opens to doors for more growth as errors and debuging are more clear that other languages.

# Ch 2 Day 1

Deployed Contract and ran a Script to confirm execution using play.onflow.org

# CH 2 Day 2

1 Explain why we wouldn't call changeGreeting in a script:
  The Script is where the transaction can solely be viewed. No changes can be made in the Script.

2 What does the AuthAccount mean in the prepare phase of the transaction?
  The AuthAccount refers to who is responsible for signing the transaction. The user who is responsible will have the data stored from the transaction on   their AuthAccount.

3 What is the difference between the prepare phase and the execute phase in the transaction?
  The prepare phase is used to access the information in the users AuthAccount, and execute phase is used to change the data in the users AuthAccount.

4 This is the hardest quest so far, so if it takes you some time, do not worry! I can help you in the Discord if you have questions.

<img width="1483" alt="image" src="https://user-images.githubusercontent.com/90923268/174441645-dca78e15-6ea7-4a21-94e3-d5f4198e2330.png">

```

pub var greeting: String
pub var myNumber: Int

pub fun changeGreeting(newGreeting: String) {
    self.greeting = newGreeting
}

pub fun updateMyNumber(newNumber: Int) {
    self.myNumber = newNumber
}

init() {
    self.greeting = "Hello, World!"
    self.myNumber = 0
}

```

