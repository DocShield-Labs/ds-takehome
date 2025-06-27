# DocShield Takehome Assessment

## Overview
Your goal is to create an AI Chat web application.

<img width="1724" alt="chat-page" src="https://github.com/user-attachments/assets/a108b9d0-b516-4b26-93e9-f33e336ddd8e" />

## Tech Stack
- React
- Next.js
- TypeScript
- Tailwind CSS
- OpenRouter (you will have received an API key in your email)

## Level 1 Requirements
- Select model: the user should be able to choose between: gpt-4o and claude-4-sonnet.
- Chat: the user should be able to chat with the selected model and see the responses in a chat interface.
- Chat History: the user should be able to see the chat history and create new chats.
- Set up a local SQLite database to store the chat history.

## Level 2 Requirements
- Chat Search: the user should be able to search the chat history via a search modal.
- File upload: the user should be able to upload a file to the chat.
- Chat compaction: the chat should automatically "compact" (summarize and add to system prompt) older messages if the context window gets to 20%. 

## Level 3 Requirements
- Reasoning models: the user should be able to select a reasoning model and see reasoning steps in the chat (you can use: `deepseek/deepseek-r1-0528:free`).
- User accounts: simple user accounts with email and password (no need for password reset, just simple auth with jwt).
- Voice mode: the user should be able to record a voice message as input to the chat

## Submission
Upload your code to a GitHub repository and email us the link to your repo. 

## Notes
- You can test the application with a free model: `deepseek/deepseek-chat-v3-0324:free`
- You have 1 week from the day you recieve the link to this repo to complete the assessment. You **are not expected** to complete all requirements, but you should do as much as you can in the allotted time (6 hours). Do not exceed the time limit, we use the honor system.
- You **are allowed** to use AI agents for the assessment, but if you do, you must include a section in the README.md describing how you used the agent and you **must follow best practices for the agent you choose**.
- Ensure your commits are atomic and have meaningful commit messages.
- Ensure your code runs and does not have any undocumented dependencies.
