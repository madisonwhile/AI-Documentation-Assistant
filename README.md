# AI Documentation Assistant

## Overview

The AI Documentation Assistant is an automation tool that transforms long Google Docs into concise AI-generated summaries while automatically creating a new Google Doc containing the output.

This project began as an exploration into workflow automation but quickly evolved into a complete product with a frontend, backend, database integration and AI-powered document processing.

More than just building an automation, this project taught me how to design and ship a real AI application that connects multiple services into a seamless user experience.

---

## The Problem

Reading through lengthy documentation is time-consuming, especially when all you need are the key takeaways.

I wanted to build a tool that could:

- Read an existing Google Doc
- Generate a concise summary using AI
- Automatically create a new Google Doc containing that summary
- Keep a history of previous summaries for future reference

The goal was to reduce repetitive work while keeping the workflow simple and familiar.

---

## Features

- AI-powered document summarisation
- Google Docs integration
- Automatic creation of summary documents
- Summary history stored in Supabase
- Authentication
- Clean frontend interface
- End-to-end workflow automation using n8n

---

## Tech Stack

- n8n
- Lovable
- Supabase
- Google Docs API
- Google Drive API
- AI Model Integration
- Webhooks

---

## How It Works

1. The user enters a Google Docs link.
2. The frontend sends the request to an n8n webhook.
3. The workflow retrieves the document content.
4. AI generates a concise summary.
5. A new Google Doc is automatically created.
6. The summary and metadata are stored in Supabase.
7. The frontend displays the completed summary and provides a link to the new document.

---

## Challenges

This project taught me that building AI products is often less about AI itself and more about connecting systems together reliably.

Some of the biggest challenges included:

- Managing webhook responses
- Handling Google authentication and permissions
- Returning structured data between the frontend and backend
- Designing prompts that consistently produced useful summaries
- Logging and displaying user history through Supabase

Debugging these integrations became one of the most valuable parts of the project.

---

## What I Learned

This was the first project where I experienced the full development lifecycle of an AI product.

It strengthened my understanding of:

- Workflow automation
- API integrations
- Database design
- Frontend and backend communication
- Error handling
- Building products around AI rather than simply using AI

More importantly, it reinforced that great user experiences come from making complex systems feel simple.

---

## Future Improvements

Some ideas I'd like to explore in future versions include:

- Multiple summarisation styles
- PDF and document upload support
- Email intergration
- AI chat with uploaded documents
- Team workspaces
- Improved dashboard and analytics

---

