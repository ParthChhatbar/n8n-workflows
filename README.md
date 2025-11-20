# 🤖 AI-Powered Business Automation Suite

A collection of intelligent, production-ready automations built using n8n, Google Gemini, Mistral OCR, Google Sheets, Jira, Gmail, and cloud APIs.

This suite replaces manual, repetitive workflows across Product, Finance, HR, and Business Operations — using end-to-end AI automation.

## 📂 Project Overview

This repository includes four major automation systems:

## 1️⃣ Automated Requirement → Jira Pipeline
📌 Purpose:

Transform product requirement PDFs into fully prepared Jira tickets with User Stories, ACs, technical solutions, and priorities — without any manual effort.

🔧 What It Does:

Extracts text & requirements from PDF files

Generates User Stories + Acceptance Criteria using a Business Analyst AI agent

Creates Jira tickets automatically

Produces solution design via a Solution Architect AI agent

Assigns priority using a Project Manager AI agent

Logs all data to Google Sheets for transparency

🎯 Outcome:

A complete backlog creation system that converts raw documents → ready-to-develop Jira tasks.

## 2️⃣ Invoice OCR & Data Extraction System
📌 Purpose:

Automate invoice processing and eliminate manual data entry in finance workflows.

🔧 What It Does:

Detects new invoice PDFs/images in Google Drive

Performs OCR using Mistral (Doc + Image OCR)

Extracts key invoice fields using Gemini AI

Stores structured data (Invoice No, Vendor, Amount, Taxes, Date, etc.) into Sheets

Ensures files aren’t processed twice

🎯 Outcome:

Hands-free invoice digitization for finance teams — accurate, fast, and scalable.

## 3️⃣ Automated Recruitment Workflow
📌 Purpose:

Speed up hiring by automating resume analysis, candidate evaluation, and communication.

🔧 What It Does:

Fetches candidate resumes from Google Drive

Extracts candidate details (skills, experience, summary)

Scores candidate suitability using AI

Updates evaluation results in Sheets

Auto-sends emails based on status:

📞 Interview Scheduling

📨 Interview Invitation

💼 Job Offer

❌ Rejection Email

🎯 Outcome:

An AI-powered ATS-like workflow that handles end-to-end candidate processing.

## 4️⃣ Automated Financial Analysis (Vaamoz)
📌 Purpose:

Enable AI-driven financial insights for business decision-making.

🔧 What It Does:

Predicts customer churn with reasons

Forecasts next month revenue

Evaluates vendor performance scores

Updates Sheets with results

Sends automated reports to business, finance, CEO/COO

🎯 Outcome:

A complete financial intelligence engine providing early warnings, forecasts, and vendor insights.

## 🧠 Technologies & Tools Used

n8n – Workflow automation engine

Google Gemini – AI reasoning, extraction & predictions

Mistral OCR – Document & image OCR

Google Sheets – Data storage & tracking

Jira Cloud API – Ticket creation & updates

Google Drive – File triggers

Gmail – Automated email delivery

Custom APIs – Metadata & external integrations

## 📈 Architecture Summary

Each project follows the same core pattern:

Trigger (manual, Drive event, or Sheet update)

Data ingestion (PDFs, resumes, spreadsheets)

AI processing (extraction, classification, prediction)

Data output (Sheets/Jira updated automatically)

Notification (emails or logs)

## 📜 Why This Repository Exists

This repo demonstrates how businesses can automate entire departments using AI agents and no-code orchestration — reducing manual work by 70–90%, improving accuracy, and accelerating decision-making.

🎉 More projects loading… 🚀

Stay tuned — new AI-driven automations will be added soon!
