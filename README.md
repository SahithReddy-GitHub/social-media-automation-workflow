# AI-Powered Social Media Content Automation

## Overview

The **AI-Powered Social Media Content Automation** project is an automation workflow built using [n8n](https://n8n.io/) and Large Language Models (LLMs) to simplify and streamline social media content creation.

The workflow takes article URLs as input, extracts relevant information, and uses AI to generate engaging, platform-specific social media content for LinkedIn, Instagram, and X (Twitter).

This project demonstrates the practical application of AI, workflow automation, and prompt engineering to reduce manual effort in social media content generation.

## Features

- **Article-Based Content Generation:** Converts article links into social media-ready content.
- **AI-Powered Automation:** Uses LLMs to generate content based on extracted article information.
- **Multi-Platform Content Creation:** Generates tailored posts for LinkedIn, Instagram, and X (Twitter).
- **Automated Workflow:** Connects content extraction and AI generation through n8n.
- **Time Efficiency:** Reduces the manual effort involved in writing platform-specific posts.

## Workflow

1. **Input:** Provide an article URL.
2. **Content Extraction:** Retrieve and extract relevant article information.
3. **AI Processing:** Send the extracted content to an LLM.
4. **Content Generation:** Generate customized social media posts for different platforms.
5. **Output:** Produce platform-specific content ready for review and publishing.

## Technologies Used

- **n8n** – Workflow automation
- **Large Language Models (LLMs)** – AI-powered content generation
- **Prompt Engineering** – Platform-specific content customization
- **APIs & HTTP Requests** – Integration with external services

## Use Cases

- Automating social media content creation
- Repurposing articles into engaging posts
- Supporting digital marketing workflows
- Improving productivity through AI automation

## Security & Configuration

Before publishing the workflow to GitHub, sensitive information and environment-specific identifiers were replaced with placeholders in `Social Media Automation Workflow.json`.

The following values were sanitized:
- Google Sheets ID
- n8n Credential IDs
- n8n Instance ID
- Hugging Face Authorization value

### Configuration Instructions

The workflow JSON was validated to ensure it parses successfully, and the original identifiers were verified to be absent.

To use this workflow:
1. Import `Social Media Automation Workflow.json` into your n8n instance.
2. Replace the placeholders with your own Google Sheets ID and n8n instance-specific configuration values.
3. Configure the required n8n credentials for the connected services.
4. Add your Hugging Face Authorization token securely through the appropriate credential configuration.
5. Test the workflow before executing it.

**Note:** Do not commit API keys, access tokens, credential IDs, or other sensitive information to a public repository. Use n8n credentials or secure environment variables wherever possible.

## Future Improvements

- Automated publishing through social media APIs
- AI-generated hashtags and captions
- Image generation for social media posts
- Content scheduling and calendar integration
- Human-in-the-loop review and approval

## Author

**Sahith Reddy Challarapu**

- GitHub: [SahithReddy-GitHub](https://github.com/SahithReddy-GitHub)
- LinkedIn: [sahithch](https://linkedin.com/in/sahithch)

---

*Built with n8n and AI to make social media content creation smarter and more efficient.*
