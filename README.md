# Project 2
# Conversational-Chatbot-using-Amazon-Lex-v2

This is a conversational chatbot, valtour that can receive inbound and outbound calls and also chat.

<img width="798" alt="Amazon Lex Chatbot Development" src="https://github.com/user-attachments/assets/5bb9851c-4999-4fb4-acea-f5d9c6dade90" />

In this project we will build a chatbot using Amazon Lex with a hotel booking example, exploring intents, utterances, slots, and fulfillment, and integrated it with Amazon Connect to handle both voice and chat interactions via configured flows, communication widgets, and static web deployment on Amazon S3 and CloudFront. The system included configuring telephony, access settings, customer input blocks, success/error handling, and linking Connect flows to phone numbers and web chat widgets. After successful testing via the deployed website, all resources were systematically deleted to avoid costs.

# Activity Guide

1. Create and Configure the Chatbot (Amazon Lex)
- Open up Amazon Lex and ceate a new bot.
- Explore Intents, Utterances, Slots, Confirmation, and Fulfillment.
- Test the bot, create a new version, and assign an alias.

2. Set Up and Integrate Amazon Connect (Amazon Connect, Amazon Lex)
- Create an Amazon Connect instance and configure access, identity, telephony, and storage settings.
- Add the Amazon Lex bot to Connect, create a contact flow, and integrate intents with user input blocks.
- Claim phone numbers, configure chat/voice widgets, and test flows for success and error scenarios.

3. Host and Test the Bot on a Static Website (Amazon S3, CloudFront, Amazon Connect)
- Host a static website using an S3 bucket and create a CloudFront distribution for HTTPS access.
- Embed the communication widget in the website, provide the URL to Amazon Connect, and test the bot.

4. Add Communication Features to Enhance Interaction (Amazon Connect)
- Embed chat and voice call widgets into the static website.
- Configure Amazon Connect flows to handle customer inputs effectively, including prompts, success, and error handling.
- Test both chat and voice communication functionalities for smooth user interactions.

5. Finalize and Clean Up Resources (Amazon S3, CloudFront, Amazon Connect)
- Ensure all resources, including Amazon Lex bots, Connect configurations, and static websites, are functioning as expected.
- Verify integration by testing the chatbot on the static website via the provided CloudFront HTTPS URL.

 6. Delete all AWS resources (Lex, Connect, S3, and CloudFront) to avoid incurring unnecessary costs post-testing.
