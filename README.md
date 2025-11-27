# AI-Driven-Development-day6

## 🔹 Step 1 — Create Your GitHub Personal Access Token (PAT)

Open:
## https://github.com/settings/personal-access-tokens/new

Generate a Fine-grained Personal Access Token with:

✔ repo (Read & Write)

Copy the generated token and store it safely.

## 🔹 Step 2 — Store Your Token Securely

## ❗ Do NOT paste your token directly into JSON.

Create a .env file in your project:

# GITHUB_TOKEN=your_personal_access_token_here

## 🔹 Step 3 — Configure Gemini to Use GitHub MCP Server

Create or open the file:

# ~/.config/gemini/mcp.json

🔹 Step 4 — Restart Gemini CLI

Run:

## gemini

## 🔹 Step 5 — Verify Connection

Run inside Gemini:

# /tools
