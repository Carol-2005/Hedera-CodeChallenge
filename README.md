Hedera HCS Messaging App

A simple Node.js project demonstrating how to use the Hedera Consensus Service (HCS) to create a topic, send encrypted messages, and retrieve/decrypt them from the Hedera network.

Features

Create or use an existing HCS topic

Send encrypted messages

Retrieve and decrypt messages

Filter messages by keyword (e.g., “Hedera”)

Clean and minimal project structure

Tech Stack

Node.js

Hedera SDK (JavaScript)

Crypto (AES encryption)

How to Run

Install dependencies:

npm install


Add your .env file:

OPERATOR_ID=your-id
OPERATOR_KEY=your-private-key
TOPIC_ID=optional-existing-topic


Start the app:

node index.js
