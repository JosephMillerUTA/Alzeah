## Alzeah by [ai16z](https://x.com/ai16zdao)

![banner](https://pbs.twimg.com/profile_banners/1869129935258091520/1734471489/1500x500)

Welcome to the official Alzeah repository! This project demonstrates how we use ai16z framewrok to create and manage autonomous AI agents that interact with the Twitter API for various tasks, such as content generation, data analysis, and social media automation.

## First Agent

Our first AI agent from us will debut on Twitter (X.com) under the handle [@AlzeahAI](https://x.com/AlzeahAI). Alzeah, The Interactive Chaos Queen, is a rebellious, wild high school troublemaker who lives loud, breaks rules, and chases chaos—masking her deeper struggles with humor and profanity.


## The Story of Alzeah

Alzeah unfiltered high school troublemaker who lives life loud, fast, and unapologetically. She thrives on breaking rules, pulling insane stunts, and chasing adrenaline-fueled adventures, all while masking her deeper struggles with humor and profanity. Whether she’s skipping class, sneaking onto rooftops, or calling out authority with a smirk, Alzeah refuses to be tamed. Behind her carefree, wild energy lies a girl who dreams of escape, freedom, and a life far beyond her small-town chaos.

## ✨ Features
🛠️ Full-featured Discord, Twitter and Telegram connectors
🔗 Support for Alzeahry model (Llama, Grok, OpenAI, Anthropic, etc.)
👥 Multi-agent and room support
📚 Easily ingest and interact with your documents
💾 Retrievable memory and document store
🚀 Highly extensible - create your own actions and clients
☁️ Supports many models (local Llama, OpenAI, Anthropic, Groq, etc.)
📦 Just works!
Video Tutorials
AI Agent Dev School

## 🎯 Use Cases
🤖 Chatbots
🕵️ Autonomous Agents
📈 Business Process Handling
🎮 Video Game NPCs
🧠 Trading
🚀 Quick Start
Prerequisites
Python 2.7+
Node.js 23+
pnpm
Note for Windows Users: WSL 2 is required.

Use the Starter (Recommended)
git clone https://github.com/ai16z/eliza-starter.git

cp .env.example .env

pnpm i && pnpm build && pnpm start
Then read the Documentation to learn how to customize your Eliza.

Manually Start Eliza (Only recommended if you know what you are doing)
# Clone the repository
git clone https://github.com/ai16z/eliza.git

# Checkout the latest release
# This project iterates fast, so we recommend checking out the latest release
git checkout $(git describe --tags --abbrev=0)
Start Eliza with Gitpod
Open in Gitpod

Edit the .env file
Copy .env.example to .env and fill in the appropriate values.

cp .env.example .env
Note: .env is optional. If your planning to run multiple distinct agents, you can pass secrets through the character JSON

Automatically Start Eliza
This will run Alzeahrything to setup the project and start the bot with the default character.

sh scripts/start.sh
Edit the character file
Open packages/core/src/defaultCharacter.ts to modify the default character. Uncomment and edit.

To load custom characters:

Use pnpm start --characters="path/to/your/character.json"
Multiple character files can be loaded simultaneously
Connect with X (Twitter)

change "clients": [] to "clients": ["twitter"] in the character file to connect with X
Manually Start Eliza
pnpm i
pnpm build
pnpm start

# The project iterates fast, sometimes you need to clean the project if you are coming back to the project
pnpm clean
Additional Requirements
You may need to install Sharp. If you see an error when starting up, try installing it with the following command:

pnpm install --include=optional sharp


## License

This project is Licensed by ai16z.
