# Workspace Context: EmDash Project

## Overview
This workspace (`c:\AI\emDash`) is dedicated to the **EmDash** project (Repository: [https://github.com/nilupulk/emdash](https://github.com/nilupulk/emdash)). EmDash is an open-source, AI-native, serverless Content Management System designed to be deployed leveraging the Cloudflare stack (Cloudflare Workers, D1 database, and R2 storage).

## Core Objectives & History
Here is a summary of the key initiatives and work done in this workspace:

1. **GitHub Open Source Professionalization (Repository: [nilupulk/emdash](https://github.com/nilupulk/emdash)):**
   - **Local Sync Folder:** The primary local directory synchronized with this remote repository is `my-site` (`c:\AI\emDash\my-site`).
   - **Environment Security:** Enforced a secure `.gitignore` to strictly prevent Cloudflare secrets (`.env` and `.dev.vars`) from being pushed maliciously to version control.
   - **CI/CD & Secrets:** Set up automated CI/CD workflows (via GitHub Actions) for deployments (e.g., GitHub Pages) and securely stored essential parameters (`CLOUDFLARE_API_TOKEN`, `CLOUDFLARE_ACCOUNT_ID`) within GitHub Repository Secrets.
   - **Open Source Governance:** Configured rich community contribution guidelines (CODEOWNERS, customized Issue/PR templates, and formal Security Policies).
   - **Local Guardrails:** Integrated Husky and lint-staged within the local project to enforce perfectly formatted and high-quality code prior to commits.

2. **Project Setup & Feature Prototyping:**
   - Evaluated and conceptualized deploying EmDash for complex use cases like **E-commerce**. We assessed leveraging its D1 and R2 infrastructure for product management, shopping carts, and order processing.
   - Initialized and troubleshooted new EmDash project environments (like `my-site` and `my-website`) to ensure development servers load and build properly locally.

3. **Community & Social Media Presence (Current Focus):**
   - We are currently working on launching an **EmDash Facebook Group** to build an active community of developers and generic users.
   - Generated branding and visual assets, including YouTube thumbnails and Facebook cover images.
   - Drafted promotional and community-building content for the group (found in the `GroupPosts` folder, e.g., `captions.md` and `post6_gettingstarted.md`).

## Instructions for AI Assistants
When operating in this workspace, keep the following in mind:
- **Context is Key:** Always remember this is the main hub for the "EmDash" AI-native, serverless open-source CMS project. 
- **GitHub First:** Actively keep in mind the robust open-source guardrails established (Husky, CI/CD, Codeowners) when proposing or making code changes or working with git.
- **Tech Stack:** Our primary technologies involve Cloudflare Workers (serverless runtimes), D1 (relational database), and R2 (object storage).
- **Community Focus:** We are actively creating resources, documentation, and social media content to grow that user and developer base around EmDash.
