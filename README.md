# Telegram AI Music Assistant

An AI-powered Telegram chatbot built with n8n, Google Gemini, and Google Sheets.

The assistant allows users to interact with a music dataset using natural language and instantly retrieve song information without writing queries or manually searching spreadsheets.

## Features

- Search songs by title
- Filter songs by release year
- Find songs by mood or genre
- Retrieve artist information
- Get oldest and newest songs
- List songs within a specific date range
- Natural language interaction through Telegram
- Context-aware conversations using memory

## Tech Stack

- n8n
- Google Gemini
- Telegram Bot API
- Google Sheets
- AI Agent
- Simple Memory

## Workflow
<img width="1361" height="512" alt="Screenshot 2026-07-30 011656" src="https://github.com/user-attachments/assets/caaf2eab-a6e7-4e5b-b7e5-ca1b0c6a1e92" />

Telegram User
↓
Telegram Trigger
↓
AI Agent (Google Gemini)
↓
Google Sheets Tool
↓
AI Response
↓
Telegram Reply

## Example Queries

- Show me 2 sad songs with their artists
- List songs released in 2022
- What is the oldest song in the dataset?
- List all songs released between 2000 and 2010
- Show romantic songs

## Project Goal

To demonstrate how Large Language Models can interact with structured data stored in Google Sheets and provide intelligent conversational responses through Telegram.

## Author

Rana Fayez
Data Science Student
