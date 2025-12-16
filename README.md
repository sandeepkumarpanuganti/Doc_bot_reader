want to build a web-based chatbot application that can read user-uploaded documents, parse their contents, store the extracted data in memory, and answer user questions based only on the document content.

Project Requirements:
1. Core Functionality

Users can upload documents (PDF, TXT, DOCX).

The chatbot should:

Read and parse the document.

Extract and store all text in memory (no database).

Answer user questions using ChatGPT API, strictly based on the uploaded document.

If a question is unrelated to the document, respond with a clear message like "The answer is not available in the uploaded document."

2. Frontend

Built using ReactJS, JavaScript, HTML, and CSS.

Features:

File upload interface.

Chat UI (user messages + bot responses).

Loading indicators and basic error handling.

Clean and minimal UI.

3. Backend

Built using Python FastAPI.

Responsibilities:

Handle file uploads.

Parse document text.

Store extracted content in memory (e.g., Python variables).

Send document context + user questions to the ChatGPT API.

Return responses to the frontend.

No database usage.

No virtual environment setup required.

4. AI Integration

Use OpenAI ChatGPT API.

Implement prompt engineering so the model:

Answers only from document context.

Does not hallucinate information.

5. Output Expectations

Provide:

Backend FastAPI code (with endpoints).

Frontend React components.

Example prompts sent to ChatGPT.

Explanation of how document parsing and in-memory storage works.

Simple project structure.

Constraints

No database.

In-memory storage only.

No authentication.

Keep the solution simple and beginner-friendly.
