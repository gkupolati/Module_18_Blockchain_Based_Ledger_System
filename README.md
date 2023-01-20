# Module_18_Challenge_Blockchain_based_Ledger_System -pychain.py 

# Overview of the project and project goal

The task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger will allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.
In order to achieve this, the following updates were made to the provided Python file for this Challenge, which already contains the basic PyChain ledger structure:
### Creating a new data class named Record. This class will serve as the template for the financial transaction records that the blocks of the ledger will store.
### Changing the existing Block data class by replacing the generic data attribute with a record attribute that is of type Record.
### Creating additional user input areas in the Streamlit application. These input areas will collect the relevant information for each financial record that will be stored in the PyChain ledger.
### Testing the completed PyChain ledger.


# Step 1: Create a Record Data Class

![image](https://user-images.githubusercontent.com/110797348/213633870-4941c004-1ad0-48ab-8b22-04fee9bf2fc7.png)
Create a new data class named `Record`. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger
will store.

# Step 2: Modify the Existing Block Data Class to Store Record Data
Change the existing `Block` data class by replacing the generic `data` attribute with a `record` attribute that’s of type `Record`.

# Step 3: Add Relevant User Inputs to the Streamlit Interface
Create additional user input areas in the Streamlit application. These input areas should collect the relevant information for each financial record
that you’ll store in the `PyChain` ledger.

# Step 4: Test the PyChain Ledger by Storing Records
Test your complete `PyChain` ledger.
![Screenshot_20230120_020934](https://user-images.githubusercontent.com/110797348/213638200-d587af90-dbb7-4ac6-b0f0-f387d1724a81.png)
![Screenshot_20230120_020958](https://user-images.githubusercontent.com/110797348/213638215-d1f94139-4c33-4811-971c-cad03583521e.png)
![Screenshot_20230120_021025](https://user-images.githubusercontent.com/110797348/213638229-6127aba2-f0ce-4db1-926e-4a1a89b33e79.png)
![Screenshot_20230120_021113](https://user-images.githubusercontent.com/110797348/213638240-cd3ccf68-7304-4413-84e4-17296fe10c0a.png)

# Libraries
### Import the required libraries and dependencies
![Screenshot_20230120_021540](https://user-images.githubusercontent.com/110797348/213638754-3f37d5ff-a93a-47e8-acdb-7c71be7ad3f8.png)
