# n8n Workflows

A simple repository of existing n8n workflows for easy sharing and version control.

## Repository Structure

```
workflows/
├── slack_workflows/     # Slack integration workflows
│   └── working_slack_webhook_n8n_workflow.json
```

## Usage

1. Download the workflow JSON file you need
2. Import it into your n8n instance:
   - Open n8n
   - Go to Workflows
   - Click "Import from File"
   - Select the downloaded JSON file

## Workflows

### Slack Workflows

- **working_slack_webhook_n8n_workflow.json** - Slack webhook integration workflow

## Contributing

Feel free to add your own n8n workflows by:
1. Creating a new directory for your workflow category
2. Adding your workflow JSON files
3. Updating this README with a description

## Notes

- Workflow files contain credential IDs that are specific to each n8n instance
- You'll need to configure your own credentials after importing
- Test workflows in a development environment before using in production