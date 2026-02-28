## Docker

### Backup Data
`cp -r ~/n8n_data ~/n8n_data_backup`
### Backup Workflow
`docker exec -u node -it <container_name> n8n export:workflow --all > workflows.json`
