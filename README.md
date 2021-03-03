# Blockchain Project
Basic BlockChain Demo App in Python

## Problem Statement: 
The government of India wants a secure and encrypted application to handle the tax filing transactions of the employees. They want to be able to back-trace all the transactions and want to have an approval system in place to verify individual transactions.

## Steps to follow:
To load dependencies:

pip install -r requirements.txt

Easiest way to run the whole thing is to do it locally:

To run couple of nodes - you can multiply them by e.g. setting various port numbers. E.g. python blockchain/blockchain.py -p 5001 and python blockchain/blockchain.py -p 5002

To run couple of clients - same trick: e.g. python blockchain_user/blockchain_client.py -p 8081 and python blockchain_user/blockchain_client.py -p 8082
