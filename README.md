# Add-Custom-Slots-to-a-Lex-Chatbot
A conversational banking chatbot built with Amazon Lex, featuring custom slot types, slot prompts, failure responses, and a fully designed multi‑turn dialog flow.
“In today’s project, I used Amazon Lex to build a conversational banking chatbot that can understand user requests and guide them through checking their account balance.”
— from your uploaded document

Project Overview
This project demonstrates how to design a realistic, multi‑turn banking conversation using Amazon Lex. The chatbot collects structured information such as:

Account type (via a custom slot type)

Date of birth (with validation and failure prompts)

Lex handles the natural‑language understanding (NLU), slot filling, and dialog management, allowing the chatbot to guide users through checking their account balance.

Features
Custom Slot Types
You created a restricted slot type to ensure Lex only accepts valid account types supported by your fictional bank.

“By defining values like checking, savings, and others, Lex can reliably capture the user’s account type…”

Intent + Slot Integration
The custom slot is linked to the CheckBalance intent, ensuring the bot collects the correct information during the conversation.

Sample Utterances with Slots
Utterances like:

Code
What’s the balance in my {accountType} account?
allow Lex to extract slot values directly from natural user input.

Failure Prompts & Validation
You added multiple variations for invalid date-of-birth inputs to keep the conversation natural and helpful.

“Umm, that didn’t work either. Try sharing your date of birth in MM/DD/YY.”

What is Amazon Lex?
Amazon Lex is AWS’s conversational AI service that provides:

Natural‑language understanding (NLU)

Automatic speech recognition (ASR)

Dialog management

Slot filling and validation

You used Lex to build a banking chatbot capable of guiding users through structured tasks like checking their account balance.

Project Steps
Designed the CheckBalance intent

Created custom slot types for account types

Added slot prompts and failure responses

Inserted slot values into sample utterances

Tested the full multi‑turn conversation in Lex

“This project took me a few focused hours… to ensure the chatbot behaved naturally and reliably.”


<img width="1181" height="515" alt="Screenshot 2026-05-03 112159" src="https://github.com/user-attachments/assets/2a48334b-b0d3-4dc4-acc6-f53a97347bbc" />

<img width="1149" height="583" alt="Screenshot 2026-05-03 114710" src="https://github.com/user-attachments/assets/db497f8e-bdd0-43eb-8067-acd2ae171901" />

<img width="501" height="549" alt="Screenshot 2026-05-03 121959" src="https://github.com/user-attachments/assets/3e4d725d-d1df-4705-a1c9-ffb9013166ab" />

<img width="1223" height="434" alt="Screenshot 2026-05-03 144408" src="https://github.com/user-attachments/assets/c6309dad-d5e2-4f59-8f68-2b7b1ac43203" />


👤 Author
Danford Amos  
📧 deeamos2002@gmail.com
