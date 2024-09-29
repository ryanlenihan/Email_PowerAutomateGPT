# Email Productivity with AI and Robotic Process Automation

![Email AI Assistant](https://ek6nypma3jc.exactdn.com/wp-content/uploads/2024/09/b7004048-a68a-443b-a18d-64d7b4669509.jpg?strip=all&lossy=1&w=1060&ssl=1)

## Overview

This repository contains the Power Automate flow configurations for an AI-powered email assistant. The tool is designed to enhance email productivity by leveraging artificial intelligence and robotic process automation techniques.

## Features

- Automatic email summarization
- AI-generated response suggestions
- Integration with Microsoft Teams for efficient communication
- Customizable email processing rules

## How It Works

1. The flow is triggered when a new email arrives in the specified inbox.
2. It processes the email content, including subject, body, and attachments.
3. Using AI (powered by GPT), it generates a summary of the email and suggests potential responses.
4. The summary and response options are sent to the user via Microsoft Teams.
5. The user can choose a response directly from Teams, which is then used to reply to the original email.

## More Details

For a comprehensive explanation of this tool and its capabilities, please refer to the following blog post:

[Email Productivity with AI and Robotic Process Automation](https://digitalbbq.au/index.php/2024/10/24/email-productivity-with-ai-and-robotic-process-automation/)

## Repository Contents

- `AskChatGPT-6B57E6EC-9301-EE11-8F6E-000D3A8E8068.json`: Configuration for the ChatGPT integration
- `SummariseEmailWithGPT-9294BD3A-9501-EE11-8F6E-000D3A8E8068.json`: Email summarization flow
- `SummariseEmailWithGptSendToTeams-1B160AE1-E501-EE11-8F6E-000D3A8E8068.json`: Teams integration flow
- `customizations.xml`: Custom configurations for the Power Automate environment
- `solution.xml`: Solution manifest for the Power Automate flows

## Note

The configurations in this repository have been sanitized to remove any sensitive or personal information. You will need to replace placeholder values with your own connection references, file IDs, and other specific details when implementing these flows.

