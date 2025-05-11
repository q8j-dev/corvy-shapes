# Shapes on Corvy [JS]!

A basic implementation of shapes.inc into corvy.chat.

# Set Up Guide

-----------------------------------------------------

## 1. Prerequisites

Make sure you have the following installed:

Node.js (v16+ recommended)
`npm` or `yarn`

## 2. Project Setup

Create your project folder and files:

`mkdir shape-corvy
cd shape-corvy
touch bot.js config.env
npm init -y`

## 3. Install Dependencies

Install the required Node.js packages:

`npm install dotenv axios openai`

## 4. Configure config.env

Open `config.env` and add:

` SHAPESINC_API_KEY=your_shapes_api_key
SHAPESINC_SHAPE_USERNAME=your_shapes_model_name
CORVY_BOT_TOKEN=your_corvy_bot_token `

Replace with your actual API keys and model name.

## 5. Run the Bot

`node bot.js`

## 6. Confirm It’s Working

Go to your flock/nest where the bot is active and try commands like:

!ask How does gravity work?

!imagine A Corvus flying in the sky

The bot should reply with either text or image URLs.



