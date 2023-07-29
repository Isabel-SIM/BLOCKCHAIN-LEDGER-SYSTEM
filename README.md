<h1>PyChain Ledger</h1>

<h5>Introduction</h5>
As a fintech engineer working at one of the largest banks in the world, I have been assigned the task of building a blockchain-based ledger system with a user-friendly web interface. This ledger will allow partner banks to conduct financial transactions and verify the integrity of the data in the ledger. To achieve this, I have made the following updates to the provided Python file, pychain1.py.

<br><br>

<h5>Step 1: Create a Record Data Class</h5>
I defined a new Python data class named Record that serves as the blueprint for the financial transaction records that the blocks of the ledger will store. The Record class has three attributes: sender, receiver, and amount. Each attribute has a specified data type, with sender and receiver being a str type, and amount being of a float type.

<br><br>

<h5>Step 2: Modify the Existing Block Data Class to Store Record Data</h5>
I renamed the data attribute in the Block class to record and set it to use an instance of the new Record class. This allows the Block to store transaction data in the form of a Record.

<br><br>

<h5>Step 3: Add Relevant User Inputs to the Streamlit Interface</h5>
I coded additional input areas in the Streamlit application to capture the sender, receiver, and amount for each financial transaction to be stored in the Block record. The user can interact with the web interface to input transaction details and add blocks to the blockchain.

<br><br>

<h5>Step 4: Test the PyChain Ledger by Storing Records</h5>
How to Run the Streamlit Application<br>
1. In the terminal, navigate to the project folder where you've coded this assignment.<br>
2. In the terminal, run the Streamlit application by using streamlit run pychain.py.<br>
3. Enter values for the sender, receiver, and amount, and then click the "Add Block" button. Do this several times to store several blocks in the ledger.<br>
4. Verify the block contents and hashes in the Streamlit dropdown menu.<br>

## Screenshots

![The Pychain Ledger](https://github.com/Isabel-SIM/WEEK-EIGHTEEN-HOMEWORK/blob/main/IMAGES/Screenshot1.png) <br>
<br>
Block Inspector Records: <br>
(https://github.com/Isabel-SIM/WEEK-EIGHTEEN-HOMEWORK/blob/main/IMAGES/Screenshot2.png) <br>
(https://github.com/Isabel-SIM/WEEK-EIGHTEEN-HOMEWORK/blob/main/IMAGES/Screenshot3.png) <br>
(https://github.com/Isabel-SIM/WEEK-EIGHTEEN-HOMEWORK/blob/main/IMAGES/Screenshot4.png) <br>

<br>

<h5>Conclusion</h5>
With these updates, the PyChain Ledger now allows partner banks to conduct financial transactions, store records securely, and verify the integrity of the data in the ledger. The Streamlit interface makes it easy for users to interact with the blockchain and manage transactions effectively.
