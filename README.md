# AI-post-trend-to-linkedin Pipeline (n8n)

An automated [n8n](https://n8n.io/) workflow that fetches top daily topics from Google Trends, uses AI to write engaging posts, and automatically publishes them to LinkedIn.

## Features
* **Automated Scheduling:** Runs daily at 9:00 AM UTC.
* **Trend Extraction:** Pulls the top 3 trending topics from Google Trends.
* **AI Content Generation:** Leverages AI to write context-aware LinkedIn posts based on current trends.
* **Auto-Publishing:** Pushes content directly to a LinkedIn profile.
* **Notifications:** Sends a summary email after execution.

## Prerequisites
To run this workflow, you will need:
* An active n8n instance
* LinkedIn Developer API credentials
* An API key for your preferred AI node (e.g., OpenAI, Anthropic)

# _Execution WorkFlow_
  <img width="1919" height="915" alt="exe-workflow" src="https://github.com/user-attachments/assets/f21a8d23-4af2-4105-91fb-c5bdb8e5c2d9" />

# _Live Post Automation_
 <img width="1370" height="805" alt="linkedIn-post" src="https://github.com/user-attachments/assets/74b8c6e6-2096-467a-b818-6789cf8ee606" />


## How to Import
1. Download the `.json` file from this repository.
2. Open your n8n workspace.
3. Click the `...` menu in the top right of your workflow canvas and select **Import from File**.
4. Upload the JSON file.
5. Double-click the LinkedIn and AI nodes to connect your own credentials.
6. Click **Execute Workflow** to test, then set it to **Active**.
