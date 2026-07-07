# AI-Powered Cover Letter Generator

An AI-powered workflow built with **n8n** and **OpenAI GPT-4** that generates personalized, ATS-friendly cover letters by analyzing a candidate's resume and the target job description.

The workflow automates the entire cover letter creation process while allowing users to customize writing style, word limit, and additional context.

---

## Features

- Resume and Job Description Analysis
- AI-generated personalized cover letters
- Multiple writing styles
  - Startup Focused
  - MNC Focused
- Configurable word limits
- Additional achievements and company connection support
- Human-like writing with advanced prompt engineering
- ATS-friendly output
- Fully automated using n8n

---

## Workflow

```
User Input
     │
     ▼
Resume + Job Description
     │
     ▼
n8n Form Trigger
     │
     ▼
GPT-4 Prompt Processing
     │
     ▼
Personalized Cover Letter
     │
     ▼
Generated Output
```

---

## Tech Stack

- n8n
- OpenAI GPT-4
- Prompt Engineering
- Workflow Automation

---

## Input Fields

- Job Description
- Resume
- Writing Style
- Preferred Word Limit
- Additional Achievements
- Company Connection

---

## Project Structure

```
AI-Powered-Cover-Letter-Generator/
│
├── workflow.json
├── README.md
└── assets/
```

---

## How to Use

1. Import the workflow into n8n.
2. Configure your OpenAI credentials.
3. Run the workflow.
4. Fill in the required form fields.
5. Generate a personalized cover letter.

---

## Future Improvements

- PDF Resume Upload
- DOCX Parsing
- Multi-language Support
- One-click PDF Export
- Email Integration
- LinkedIn Profile Import
- Multiple AI Model Support

---

## Skills Demonstrated

- Workflow Automation
- Prompt Engineering
- AI Application Development
- LLM Integration
- OpenAI API
- n8n Automation
- Document Generation
- Resume Parsing
- ATS Optimization

---

## License

This project is for educational and portfolio purposes.
