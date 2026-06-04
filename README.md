# GTM AI Agent — WhatsApp to CRM Automation Pipeline

An end-to-end AI-powered sales automation workflow that captures prospect details via WhatsApp, auto-logs them to HubSpot CRM, and triggers a personalized outreach email — all from a single conversation.

## The Problem

Enterprise sales professionals lose hours manually logging prospect information into CRM after calls and meetings. Notes get lost, follow-ups are delayed, and deals slip through the cracks.

## The Solution

A conversational automation pipeline where a sales rep types prospect details naturally into WhatsApp. The agent handles everything else — no manual CRM entry, no copy-pasting, no delays.

## How It Works

1. **Sales rep opens WhatsApp** and describes the prospect conversationally
2. **n8n workflow triggers** via Twilio/WhatsApp Business API
3. **Data is validated and structured** automatically
4. **HubSpot API creates** Company + Contact + Deal records in one chained call
5. **Personalized image, audio, email, whatsApp content fires** instantly to the prospect with AI-generated content
6. **Record saved to Google Drive** for team visibility

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Workflow Automation | n8n (self-hosted on Oracle Cloud) |
| Messaging | Twilio + WhatsApp Business API |
| CRM | HubSpot API (Companies, Contacts, Deals) |
| Image Generation | Adobe Firefly + Cloudinary |
| Audio Generation | ElevenLabs |
| Storage | Google Drive API |
| Infrastructure | Oracle Cloud VM (zero cost) |

## What's in This Repo

- `gtm-agent-workflow.json` — Full n8n workflow export. Import directly into any n8n instance to run the pipeline.

## Live Demo

▶️ [Watch the 2-minute demo](https://spectrum-science-350.notion.site/Abhinaya-Ravi-AI-Automation-Portfolio-365ace8a70d38024ad94f324059b53ed)

Full portfolio and documentation available at the link above.

## About

Built independently from scratch in under a week — no prior API experience. Used AI as an engineering co-pilot to learn REST APIs, chain HubSpot API calls, configure Twilio webhooks, and deploy a self-hosted n8n instance on Oracle Cloud.

**Author:** Abhinaya Ravi — GTM Enablement Leader & AI Workflow Builder  
[LinkedIn](https://www.linkedin.com/in/abhinaya-ravi-a5b30018) | [Portfolio](https://spectrum-science-350.notion.site/Abhinaya-Ravi-AI-Automation-Portfolio-365ace8a70d38024ad94f324059b53ed)
