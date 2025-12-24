# Google Gemini Interactions API Demo

A comprehensive Jupyter notebook demonstrating the key features of Google's Gemini Interactions API - a unified interface for interacting with Gemini models and agents.

## Overview

The Interactions API simplifies state management, tool orchestration, and long-running tasks when building AI applications with Gemini models.

## Features Demonstrated

- ✅ **Basic Interactions** - Simple text prompts
- ✅ **Stateful Conversations** - Multi-turn conversations with server-side state management
- ✅ **Retrieving Past Interactions** - Access previous conversation turns
- ✅ **Stateless Conversations** - Client-side conversation history management
- ✅ **Background Execution** - Asynchronous long-running tasks
- ✅ **Best Practices** - Storage, retention, and optimization tips

## Setup

1. **Install dependencies:**
   ```bash
   pip install google-genai>=1.56.0 python-dotenv
   ```

2. **Get your API key:**
   - Visit [Google AI Studio](https://aistudio.google.com/app/apikey)
   - Create or copy your API key

3. **Configure environment:**
   - Create a `.env` file in the directory where the notebook is running.
   - Add your API key:
     ```
     GEMINI_API_KEY=your_api_key_here
     ```

4. **Run the notebook:**
   - Open `google_interaction_api/demo_google_interation_api.ipynb`
   - Execute cells sequentially

## Supported Models

- `gemini-2.5-pro`
- `gemini-2.5-flash`
- `gemini-2.5-flash-lite`
- `gemini-3-pro-preview`
- `gemini-3-flash-preview`

## Key Benefits

- **Server-side state management** - No need to resend entire chat history
- **Improved performance** - Implicit caching reduces costs
- **Simplified API** - One interface for models and agents
- **Background execution** - Handle long-running tasks asynchronously

## Documentation

- [Official API Documentation](https://ai.google.dev/gemini-api/docs/interactions)
- **Note:** The Interactions API is currently in Beta. Features and schemas are subject to breaking changes.

## License

This is a demo/educational project. Please refer to Google's API terms of service for usage guidelines.

