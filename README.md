<div align="center">

# 🔎 EduSearch

### Academic Information Retrieval Search Engine

**Search smarter. Discover relevant academic resources, notes, books, and learning materials through relevance-based information retrieval.**

<br>

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_EduSearch-2563EB?style=for-the-badge&logo=vercel&logoColor=white)](https://edusearch-ir.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Source_Code-181717?style=for-the-badge&logo=github)](https://github.com/Prajwalasri-1209/EduSearch)

<br>

![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?style=flat-square&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?style=flat-square&logo=vercel)

</div>

---

## Overview

**EduSearch** is a web-based Information Retrieval system built to provide a focused academic search experience.

It processes user queries, retrieves relevant academic resources, calculates relevance scores, and ranks results to help users quickly discover useful learning material.

The project demonstrates how core **Information Retrieval (IR)** concepts can be applied in a practical full-stack application.

---

## Preview

### Search & Discover

![EduSearch Homepage](screenshots/home.png)

### Ranked Search Results

![EduSearch Search Results](screenshots/search-results.png)

### Add Your Own Documents

![EduSearch Add Document](screenshots/add-document.png)

---

## Key Features

| Feature | Description |
|---|---|
| 🔎 **Academic Search** | Search for academic topics and learning resources |
| 📊 **Relevance Ranking** | Results are ranked according to their relevance to the query |
| 📚 **Books & Resources** | Discover books and educational resources |
| 📝 **Study Notes** | Access topic-focused learning material |
| 📄 **Document Search** | Add and search through custom documents |
| 🌐 **External Sources** | Retrieve information from supported web and academic sources |
| 🧠 **IR Lab** | Explore and understand Information Retrieval concepts |
| ⚡ **Responsive UI** | Fast and clean search experience across devices |

---

## How It Works

```text
                    ┌──────────────────┐
                    │    User Query    │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ Text Processing  │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ Document Index   │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ Relevance Score  │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ Result Ranking   │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ Ranked Results   │
                    └──────────────────┘
```

EduSearch transforms the user's query into a representation that can be compared against indexed documents. Relevance scores are calculated and the most relevant resources are presented first.

---

## Information Retrieval Concepts

EduSearch explores several fundamental IR techniques:

- **Text Preprocessing** — preparing raw text for retrieval
- **Tokenization** — splitting text into searchable units
- **Normalization** — standardizing text before comparison
- **Document Indexing** — organizing documents for efficient retrieval
- **TF-IDF** — representing term importance within documents
- **Cosine Similarity** — measuring similarity between query and document vectors
- **BM25** — relevance-based document ranking
- **Relevance Scoring** — assigning scores to retrieved resources
- **Ranking** — ordering results based on relevance

---

## Tech Stack

<table>
<tr>
<td><b>Frontend</b></td>
<td>React · TypeScript · Vite · CSS</td>
</tr>

<tr>
<td><b>Backend</b></td>
<td>Node.js · TypeScript</td>
</tr>

<tr>
<td><b>Information Retrieval</b></td>
<td>TF-IDF · Cosine Similarity · BM25 · Document Indexing</td>
</tr>

<tr>
<td><b>Sources</b></td>
<td>Academic Resources · Wikipedia · Books · User Documents</td>
</tr>

<tr>
<td><b>Deployment</b></td>
<td>Vercel</td>
</tr>

<tr>
<td><b>Version Control</b></td>
<td>Git · GitHub</td>
</tr>
</table>

---

## Project Structure

```text
EduSearch/
│
├── api/
│   └── index.ts
│
├── server/
│   ├── data/
│   ├── ir/
│   │   ├── indexer.ts
│   │   ├── preprocessor.ts
│   │   └── retrieval.ts
│   ├── notes/
│   └── sources/
│
├── src/
│   ├── components/
│   ├── services/
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
│
├── screenshots/
│   ├── home.png
│   ├── search-results.png
│   └── add-document.png
│
├── index.html
├── package.json
├── server.ts
├── tsconfig.json
├── vercel.json
└── vite.config.ts
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Prajwalasri-1209/EduSearch.git
```

### 2. Enter the project directory

```bash
cd EduSearch
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start EduSearch

```bash
npm run dev
```

The development server will start locally.

---

## Live Application

EduSearch is deployed on Vercel and can be accessed here:

### [🚀 Launch EduSearch](https://edusearch-ir.vercel.app/)

---

## What We Learned

Building EduSearch helped us gain practical experience with:

- Designing an Information Retrieval pipeline
- Text preprocessing and document indexing
- Implementing relevance-based retrieval
- TF-IDF and similarity calculations
- Ranking search results
- Building React applications with TypeScript
- Backend development using Node.js
- Integrating multiple information sources
- Working with user-provided documents
- Git and GitHub workflows
- Deploying a full-stack application with Vercel

---

## Future Improvements

- Semantic search using vector embeddings
- Improved ranking and query understanding
- More academic data sources
- Search filters and advanced search
- Personalized recommendations
- Search history
- Improved PDF/document processing
- Multilingual academic search

---

## Project Credits

EduSearch is a collaborative project developed by **Manideep** and **Prajwala sri**.

- **Manideep:** [GitHub](https://github.com/Manideep-1307)
- **Prajwala Sri:** [GitHub](https://github.com/Prajwalasri-1209)

This repository is a fork of the original [EduSearch project](https://github.com/Manideep-1307/EduSearch).

---

## Contributing

Contributions and suggestions are welcome.

If you'd like to contribute:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your changes
5. Push the branch
6. Open a Pull Request

---

<div align="center">

## Try EduSearch

### [🌐 Live Demo](https://edusearch-ir.vercel.app/) · [💻 Source Code](https://github.com/Prajwalasri-1209/EduSearch)

<br>

Built with **React · TypeScript · Node.js · Information Retrieval**

<br>

⭐ **If you find EduSearch useful or interesting, consider starring the repository.**

</div>
