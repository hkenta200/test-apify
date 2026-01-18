# Apify Demo Project

This repository contains a demo project built with Apify to sample how to create, configure, and run an Apify Actor for web automation and data extraction.

The project is intended for learning, experimentation, and as a starting point for building Apify Actors.

## 🚀 Features

* Example Apify Actor structure
* Web scraping / automation using Apify SDK
* Structured output saved to Apify dataset
* Ready-to-run locally and on the Apify platform

## 🧩 Tech Stack

* Node.js
* Apify SDK
* JavaScript
* Axios
* React Native

## ⚙️ Prerequisites

* Node.js (v16 or newer recommended)
* npm or yarn
* Apify CLI (optional, but recommended)

Install Apify CLI:

```bash
npm install -g apify-cli
```

## ▶️ Running the Project Locally

1. Clone the repository:

```bash
git clone <your-repository-url>
cd <project-folder>
```

2. Install dependencies:

```bash
npm install
```

3. (Optional) Log in to Apify:

```bash
apify login
```

4. Run the Actor locally:

```bash
apify run
```

---

## 🧪 Input Configuration

The Actor accepts input defined in `INPUT_SCHEMA.json`. Example input:

```json
{
  "startUrls": [
    { "url": "https://example.com" }
  ],
  "maxPages": 10
}
```

You can modify the input when running locally or via the Apify Console.

## 📤 Output

* Extracted data is stored in the **default Apify dataset**
* Results can be viewed:

  * In the Apify Console
  * Locally in the `storage/datasets` directory
  * Via Apify API

## ☁️ Running on Apify Platform

1. Push the project to Apify:

```bash
apify push
```
2. Run the Actor from the Apify Console
3. Provide input using the UI or API

## 🧾 Notes

This is a demo project, not optimized for production use. Review Apify best practices before deploying to production.

## 📚 Resources

* Apify Documentation
* Apify SDK GitHub Repository
