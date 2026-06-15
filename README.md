# Pocket Professor 🎓

Pocket Professor is an Offline AI-Powered Study Assistant built for **OSDHack 2026**.

It helps students read PDFs, generate notes, create flashcards, build quizzes, and interact with study materials while keeping processing local to the user's device.

---

## 🚀 Features

- 📄 PDF Text Extraction
- 📝 Automatic Notes Generation
- 🎴 Flashcard Generation
- ❓ Quiz Generation
- 🤖 AI-Powered Question Answering
- 🎤 Speech-to-Text Input
- 🔊 Text-to-Speech Responses
- 📚 Local Document Library
- 🗑️ Document Management
- 🔒 Privacy-Focused Processing
- 🌐 Browser-Based Experience

---

## 🎯 Problem Statement

Students often spend a lot of time reading large documents and creating study materials manually.

Pocket Professor simplifies learning by automatically transforming PDFs into:

- Notes
- Flashcards
- Quizzes
- Question & Answer Sessions

All while keeping data on the user's device.

---

## 🧠 On-Device AI

This project aligns with the OSDHack 2026 theme by performing its core functionality directly on the user's device.

The application demonstrates:

- Browser-Based AI
- Local Document Processing
- Offline-First Design
- Privacy-Preserving Computing
- Lightweight AI Inference

No cloud AI service is required for the primary document processing workflow.

---

## 🛠️ Tech Stack

### Frontend

- HTML5
- CSS3
- JavaScript

### AI & Processing

- PDF.js
- Transformers.js
- ONNX Runtime Web
- Web Speech API

### Storage

- IndexedDB

---

## 📂 Project Structure

```text
Pocket-Professor/
│
├── index.html
├── package.json
├── package-lock.json
├── README.md
├── LICENSE
│
├── screenshots/
│   ├── home.png
│   ├── upload.png
│   ├── notes.png
│   ├── flashcards.png
│   └── quiz.png
│
└── assets/
```

---

## 📖 Usage Instructions

### Step 1: Launch the Application

Start the development server:

```bash
npm install
npm run dev
```

Open your browser and visit:

```text
http://localhost:5173
```

---

### Step 2: Upload a PDF

1. Click the **Upload PDF** button.
2. Select a PDF document from your device.
3. Wait for the extraction process to complete.
4. The document will be saved to your local library.

---

### Step 3: Read the Document

1. Open the Library panel.
2. Select a document.
3. View the extracted text directly inside the application.

---

### Step 4: Generate Notes

1. Open a document.
2. Click **Generate Notes**.
3. Pocket Professor will create concise study notes from the document content.

---

### Step 5: Generate Flashcards

1. Open a document.
2. Click **Generate Flashcards**.
3. Review automatically generated question-and-answer flashcards.

---

### Step 6: Generate a Quiz

1. Open a document.
2. Click **Generate Quiz**.
3. Practice with automatically generated quiz questions.

---

### Step 7: Ask Questions

1. Navigate to the Question & Answer section.
2. Type a question related to the uploaded document.
3. Pocket Professor will generate an answer based on the document content.

Example:

```text
What is machine learning?
Explain supervised learning.
What are the key points of Chapter 3?
```

---

### Step 8: Use Voice Features

#### Speech-to-Text

1. Click the microphone button.
2. Speak your question.
3. The application converts your speech into text.

#### Text-to-Speech

1. Generate an answer.
2. Click the Speak button.
3. Listen to the answer using voice output.

---

### Step 9: Manage Your Library

Users can:

- Open saved documents
- Delete individual documents
- Clear the entire library
- Revisit previously uploaded PDFs

---

### Step 10: Offline Usage

Pocket Professor is designed as an Offline-First application.

Core features continue to work locally in the browser without requiring cloud-based AI services.

Benefits:

- Faster response times
- Improved privacy
- Reduced internet dependency
- Local document processing

---

## Demo Workflow

1. Upload a PDF
2. Extract text
3. Generate Notes
4. Generate Flashcards
5. Generate Quiz
6. Ask Questions
7. Use Voice Features
8. Save documents in Library

This demonstrates the complete Pocket Professor study workflow.
