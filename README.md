# FX Fraud Detection Automation (n8n)

This project is a real-time FX rate validation and fraud detection workflow built using n8n.

## Features
- Webhook-based FX input
- Live market rate API integration
- Fraud detection logic using rate difference
- MySQL audit logging
- Automatic email alerts
- Monitoring dashboard queries

## Tech Stack
- n8n
- REST API
- MySQL
- JavaScript expressions
- Email automation

## How it works
User submits FX rate → system fetches live rate → compares → flags OK/FRAUD → logs → alerts.

## Files
- fx-fraud-workflow.json (n8n workflow export)

## How to use
Import JSON into n8n → configure API + DB + Email credentials → run workflow.
