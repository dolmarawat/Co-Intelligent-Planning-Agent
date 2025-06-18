# Co-Intelligent-Planning-Agent
In collaboration with BOMA and World Merit

## WM Planning Assistant – GPT-powered Co-Intelligent Chatbot

The WM Planning Assistant is a lightweight, AI-guided chatbot designed to support early-stage impact teams under the World Merit network. This assistant helps nonprofits and grassroots organizations reflect on governance, planning, messaging, and ethical practices using a conversational interface.

It is built for ease of access, self-assessment, and documentation, with a focus on helping teams:

Define roles and decision-making responsibilities

Track weekly planning prompts and reflections

Get tailored learning suggestions (Action University modules)

Build ethical awareness in messaging and operations

## How to Use This Demo

This project includes a simple HTML mockup of the chatbot interface. It is ideal for showcasing basic chatbot behavior using rule-based responses (not OpenAI API connected yet).

✅ Features

Preloaded prompts from governance, messaging, fundraising, and team culture domains

Static rule-based logic to simulate GPT response flow

Clean, embeddable interface (HTML + JavaScript only)

## Implementation on Your Platform

## File: index.html

This file contains all the chatbot UI and logic in one place. You can:

Embed in your platform (if it supports HTML block/iframe):

Use an <iframe> to load index.html

Or paste the code directly into an HTML module on low-code platforms (e.g., Webflow, Tilda, Typedream)

## Customize:

Edit mockResponse(input) in the <script> section to add more simulated GPT replies

Replace mock logic with OpenAI API calls for dynamic GPT output

## Host on GitHub Pages:

Push this repo to GitHub

Enable GitHub Pages under repo settings → select main branch → /root folder

Access via https://your-username.github.io/repo-name

Example iframe (for embed):

<iframe src="https://your-username.github.io/wm-planning-assistant" width="100%" height="500px" style="border:none;"></iframe>

## Future Development

To make this chatbot dynamic and LLM-powered:

Replace mockResponse() with an OpenAI GPT-4 API call

Add user/team-level state tracking via Firebase or Supabase

Integrate a backend (Flask/FastAPI) for report generation and dashboard sync
