# Azure DevOps and ClickUp Task Synchronization

This Python script automates the synchronization of tasks between Azure DevOps and ClickUp, allowing for seamless integration and efficient project management across both platforms.

## Features

- **Create Tasks in Azure DevOps**: Automatically generate tasks in Azure DevOps based on tasks in ClickUp.
- **Synchronize Task Statuses**: Keep task statuses in sync between Azure DevOps and ClickUp.
- **Update ClickUp Custom Fields**: Link ClickUp tasks to their corresponding Azure DevOps tasks by updating custom fields with Azure task IDs.

## Requirements

- **Python 3.6+**
- **Requests Library**: Install via `pip install requests`

## Configuration

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
2. **Set Your API Keys and Project Information:

3. **Replace the placeholders in the script (your_clickup_api_key, your_azure_personal_access_token, etc.) with your actual credentials and project information.
Run the Script:

```bash
python sync_tasks.py
```

## Usage
This script can be run manually or scheduled to run at regular intervals (e.g., using cron jobs) to keep your tasks in sync automatically.

## Learn More
For a detailed explanation of how the script works and how to configure it, check out our blog post:

🔗 [Automating Task Synchronization Between Azure DevOps and ClickUp Using Python](https://gurver.org/automating-task-synchronization-between-azure-devops-and-clickup-using-python/)


Stay Connected
Follow me on LinkedIn for more updates and automation tips:

🔗 [Connect on LinkedIn](https://www.linkedin.com/in/kim-gurinov/)
