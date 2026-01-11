

# 🧠 AI & Cybersecurity News Automation System

> A fully automated workflow that collects, summarizes, and delivers high-signal AI & cybersecurity news — without noise, bias, or manual effort.

---

## 📸 Workflow Preview
---
<img width="1809" height="763" alt="Screenshot 2026-01-10 215203" src="https://github.com/user-attachments/assets/86487c6f-98a8-4190-9cb5-fb3480d1fbab" />


---

## ❌ Problem

Keeping up with **AI and cybersecurity news** is exhausting:

* Too many sources
* Repetitive or clickbait headlines
* Time wasted reading full articles
* Inconsistent summaries
* Manual effort every single day

Most “AI summaries” online also **hallucinate or exaggerate**, which defeats the purpose.

---

## ✅ Solution

This project automates the entire pipeline — from **news collection to clean delivery**.

### What this system does:

* Fetches **AI & Cybersecurity news** from trusted RSS feeds
* Pulls **AI tech events in India** using **SerpAPI (Google Events)**
* Aggregates all inputs into a single dataset
* Uses an AI model with **strict constraints** to summarize only provided content
* Sends a **structured daily tech brief** directly via email

No fluff.
No invented content.
Only source-backed summaries.

---

## 🔁 Workflow Overview

1. **Schedule Trigger**

   * Runs automatically on a fixed schedule

2. **Data Ingestion**

   * AI news via RSS
   * Cybersecurity news via RSS
   * AI tech events via SerpAPI

3. **Aggregation**

   * Merges all sources into one clean payload

4. **AI Summarization**

   * Summarizes content using strict formatting rules
   * Limits items per category
   * Prevents hallucinations

5. **Delivery**

   * Sends final digest via Gmail automatically

---

## 🛠️ Tech Stack

* **n8n** – workflow automation
* **RSS Feeds** – real-time news ingestion
* **SerpAPI** – Google Events data for AI tech events
* **Google Gemini (via LangChain)** – controlled AI summarization
* **Gmail API** – automated email delivery

---

## 📧 Output Format

The email digest includes:

* 🤖 **AI News** (up to 3 items)
* 💻 **Cybersecurity / Tech News** (up to 3 items)
* Clear headlines
* 1–1.5 line factual summaries
* Minimal emojis for clarity

---

## 🚀 Why This Matters

This project focuses on **AI reliability**, not just automation:

* Enforces input-only summarization
* Prevents hallucinations
* Produces consistent, repeatable results
* Saves real time daily

It’s designed as a **system**, not a demo.

---

## 🧩 Customization

You can easily:

* Change RSS sources
* Modify email recipients
* Adjust schedule timing
* Add more categories
* Swap AI models

---

## 📌 Status

* ✅ Active and running
* 🔧 Continuously improving
* 🧪 Open to extensions (Slack, Notion, WhatsApp delivery)

---

## 🤝 Let’s Connect

If you’re working on:

* AI automation
* No-code workflows
* News intelligence systems
* Reliable LLM pipelines

Feel free to fork, explore, or connect.

---
