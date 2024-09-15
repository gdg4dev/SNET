# SNET | SAFE INTERNET

This repository contains two interconnected tools (divided into 4 repo) aimed at enhancing online safety and security for families: a **Chrome extension** that detects phishing and malicious websites and a **Snet lookup tool** that allows parents to verify the identity of individuals their children interact with. The repository is organized into submodules for the frontend and backend of each tool.

## Overview

This project includes:

1. **Chrome Extension**
   - Frontend: Handles the user interface and browser interactions.
   - Backend: Analyzes emails using an LLM to flag emails as dangerous, cautious, or safe.
   
2. **Snet Lookup Tool**
   - Frontend: A user interface where parents can input details (email, phone, name) to look up the identity of individuals.
   - Backend: Scrapes public information from `thatsthem.com` & `nsopw.gov` and provides results to the frontend.

## Project Structure

The repository is organized into four submodules:

```bash
SNET/
│
├── extension-frontend/    # Frontend for Chrome Extension
├── extension-backend/     # Backend for Chrome Extension (LLM Analysis)
├── snet-lookup-frontend/  # Frontend for Snet Lookup Tool
└── snet-lookup-backend/   # Backend for Snet Lookup Tool (Public Info Scraper)
