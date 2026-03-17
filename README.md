EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS


Aim:
 To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. Analyze the quality, accuracy, and depth of the generated responses.

Naïve Prompt:
What is blockchain?
 1. Meaning of Blockchain
Blockchain = Block + Chain
•	Block → A small container that stores data (like transactions).
•	Chain → These blocks are connected one after another.
So Blockchain is a chain of blocks that store information securely.
________________________________________
📚 2. Think of it like a digital notebook
Imagine a notebook that records transactions.
Example entries:
Block 1 → A sent ₹500 to B
Block 2 → B sent ₹200 to C
Block 3 → C sent ₹100 to D
Each page (block) is linked to the previous page.
If someone tries to change Block 1, the entire chain breaks.
So it becomes very difficult to hack or modify.
________________________________________
🌍 3. Special Feature – Distributed System
Normally data is stored in one server.
But in blockchain:
•	Data is stored in many computers (nodes) around the world.
•	Everyone has a copy of the same record.
So if one computer fails, the system still works.
________________________________________
🔐 4. Why Blockchain is Secure
Blockchain uses:
•	Cryptography
•	Hash functions
•	Distributed verification
Because of this:
•	Data cannot be easily changed
•	Transactions are transparent
•	No single authority controls it
________________________________________
💰 5. Where Blockchain is Used
Some common uses:
1️ Cryptocurrency – like Bitcoin and Ethereum
2️ Digital payments
3️ Supply chain tracking
4️ Medical records
5️ Voting systems
________________________________________
 One-Line Definition (For Exams)
Blockchain is a decentralized digital ledger that records transactions in blocks linked together using cryptography.
________________________________________
Basic Prompt:
Explain blockchain technology clearly. Include its definition, how it works, and one example of how it is used in digital transactions.
🔗 Blockchain Technology


 

1️⃣ Definition of Blockchain
Blockchain is a decentralized digital ledger that records transactions in a series of blocks. These blocks are securely linked together using cryptography, forming a chain.
•	Decentralized → No single authority controls it.
•	Transparent → Transactions can be verified by participants.
•	Secure → Once data is recorded, it is very difficult to change.
In simple words, blockchain is a secure digital record book shared across many computers.
________________________________________
2️⃣ How Blockchain Works
Blockchain works through a series of steps:
Step 1: Transaction Initiation
A user starts a transaction, such as sending digital money.
Step 2: Transaction Broadcast
The transaction is sent to a network of computers called nodes.
Step 3: Verification
The nodes verify the transaction using cryptographic algorithms and consensus mechanisms.
Step 4: Block Creation
Once verified, the transaction is grouped with other transactions into a block.
Step 5: Block Added to Chain
The new block is connected to the previous block using a unique cryptographic hash, forming a chain.
Step 6: Permanent Record
The transaction becomes permanent and cannot be easily altered.
________________________________________
3️⃣ Example in Digital Transactions
One common use of blockchain is in cryptocurrency transactions.
For example, in Bitcoin:
1.	A person sends Bitcoin to another person.
2.	The transaction is broadcast to the Bitcoin network.
3.	Network nodes verify the transaction.
4.	The verified transaction is added to a block.
5.	The block is added to the blockchain, creating a permanent record.
This process allows secure and transparent digital payments without a bank or intermediary.
________________________________________
✅ Summary:
Blockchain is a secure, decentralized system for recording transactions. It works by verifying transactions through a network, storing them in blocks, and linking these blocks together to create a permanent and tamper-resistant record.




Comparative Analysis Based on Quality, Accuracy, and Depth
Quality in Naive Prompt
The naive prompt “What is blockchain?” is very short and lacks specific instructions. Because of this, the AI model has to interpret what type of explanation the user wants. As a result, the generated response may vary depending on the system’s interpretation.
In many cases, the response may include:
•	A brief definition of blockchain
•	A short explanation of blocks and chains
•	Some general uses like cryptocurrency
However, the explanation may not follow a structured format. Important aspects such as how blockchain works, its components, or real-world examples might not be explained in detail. The response may also lack clear sections or headings, making it less organized.
Therefore, the quality of the answer depends largely on the AI’s assumptions rather than explicit instructions from the user.
Quality in Basic Prompt
The basic prompt provides clear instructions about what information should be included in the response. It asks specifically for:
•	Definition
•	Explanation of how it works
•	Example of digital transactions
Because the prompt clearly defines the expected output, the AI generates a well-structured response. The explanation typically includes separate sections for each requested part, improving readability and understanding.
The response is usually:
•	More organized
•	Easier to follow
•	More informative
This leads to higher response quality, because the AI knows exactly what information the user needs.
Conclusion for Quality
Basic prompts generally produce higher quality responses than naive prompts because they guide the AI toward a clearer and more structured explanation.
________________________________________
Accuracy in Naive Prompt
When a naive prompt is used, the AI provides a general explanation based on its understanding of the topic. Since the question is broad, the AI might present a simplified description.
For example, the response may state that blockchain is a secure digital ledger used in cryptocurrencies. While this statement is correct, it may omit technical aspects such as:
•	Distributed networks
•	Cryptographic hashing
•	Consensus mechanisms
Because of the limited guidance from the prompt, the explanation may remain surface-level and may not fully capture the technical meaning of blockchain technology.
However, the information itself is usually still correct; it is simply less detailed or precise.
Accuracy in Basic Prompt
The basic prompt improves accuracy because it requires the AI to explain specific components of blockchain technology.
By asking for:
•	Definition
•	Working process
•	Example of digital transaction
the prompt forces the AI to provide clear and specific explanations rather than a broad overview.
For instance, the response will usually describe:
1.	Blockchain as a decentralized digital ledger
2.	The process of transaction verification
3.	The creation and linking of blocks
4.	A real-world example such as cryptocurrency transactions
This structured requirement reduces ambiguity and encourages the AI to produce more precise and technically accurate information.
Depth in Naive Prompt
Naive prompts usually produce short and simple responses because the request is broad. The AI typically provides only the most essential information needed to answer the question.
For example, the explanation may include:
•	A basic definition
•	A simple description of blocks storing data
•	A short mention of cryptocurrencies
However, it may not explain:
•	The step-by-step process of blockchain operations
•	The role of nodes in the network
•	How blocks are validated and linked
As a result, the depth of information is limited.
Depth in Basic Prompt
Basic prompts significantly improve depth because they explicitly request multiple aspects of the topic.
In this case, the AI explains:
•	What blockchain is
•	How transactions are processed
•	How blocks are created and connected
•	How the system is used in real-world digital transactions
This leads to a more comprehensive explanation that helps the reader understand not only the definition but also the functionality and practical application of blockchain technology.
The response therefore becomes longer, more detailed, and more informative.
Aspect	Naive Prompt	Basic Prompt
Quality	Less structured, brief explanation	Well-structured and clearly organized
Accuracy	General but correct information	More precise and detailed explanation
Depth	Limited details and short overview	Comprehensive explanation with multiple aspects

Output
The experiment was conducted using two different types of prompts: a naive prompt and a basic prompt.
The naive prompt, “What is blockchain?”, generated a response that provided a general definition and a brief overview of blockchain technology. The explanation was short and covered only the basic concept without detailed structure or step-by-step explanation.
The basic prompt, “Explain blockchain technology clearly. Include its definition, how it works, and one example of how it is used in digital transactions.”, generated a more structured and detailed response. The answer included separate sections for the definition, working process of blockchain, and a practical example of its use in digital transactions. The explanation was clearer, more organized, and easier to understand.
By comparing the responses, it was observed that the basic prompt produced higher quality output with better structure, clearer explanations, and more detailed information, while the naive prompt produced a simpler and shorter response.
________________________________________
Result
From this experiment, it can be concluded that prompt design significantly affects the quality of AI-generated responses. A naive prompt provides only a general request, which results in a brief and less detailed explanation. In contrast, a basic prompt provides clear instructions about what information should be included, allowing the AI to generate a more accurate, structured, and comprehensive response.
Therefore, well-defined prompts lead to better quality, higher accuracy, and deeper explanations, making them more effective for obtaining useful information from AI systems.


