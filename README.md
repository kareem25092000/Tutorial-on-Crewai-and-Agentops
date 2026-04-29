# 🧠 CrewAI Multi-Agent Workflow with Gemini

## 📌 Overview

This project builds a **CrewAI-powered multi-agent workflow** using **Gemini (gemini-3-flash-preview)** to generate high-quality content.

It consists of **two separate agent crews**, each with a distinct purpose:

* **Crew 1: Story Generation Crew** → creates and summarizes stories
* **Crew 2: Content Creation Crew** → produces polished, accurate, and SEO-ready content

---

## ⚙️ Setup

1. Install dependencies:

```bash
pip install crewai python-dotenv agentops
```

2. Create a `.env` file and add your API key:

```env
GEMINI_API_KEY=your_key_here
```

---

## 👥 Crew 1: Story Generation Crew

### 🎯 Goal

Generate creative stories based on user input and produce concise summaries while preserving style.

### 🤖 Agents

#### 1. Egyptian Author Agent

* 10 years of experience
* Inspired by Dostoevsky
* Generates stories based on:

  * Theme
  * Main character name
  * Subject

#### 2. German Summarizer Agent

* 5 years of experience
* Summarizes the story
* Maintains the original writing style

### 📤 Output

* A short story (≤ 500 words)
* A concise, stylistically consistent summary

---

## 👥 Crew 2: Content Creation Crew

### 🎯 Goal

Generate high-quality, publishable, and SEO-friendly content.

### 🤖 Agents

#### 1. Writer Agent

* Produces long-form, well-structured articles

#### 2. Summarizer Agent

* Generates:

  * TL;DR
  * Bullet points
  * Short summaries

#### 3. Fact-Checker Agent

* Verifies technical accuracy

#### 4. Metadata Agent

* Creates:

  * SEO-friendly titles
  * Tags
  * Structured metadata

---

## 🎯 Key Objectives

* Build modular and reusable multi-agent workflows
* Automate storytelling and content generation
* Ensure high-quality outputs through multi-agent collaboration
* Enable scalable workflows using CrewAI

---

## 📦 Final Output

* Creative short stories
* Story summaries
* High-quality articles
* SEO-ready content

---
