# Example Workflow

The YAML file in this repo contains an example GitHub Actions workflow, which builds a java app with Maven, and deploys to a web app on Azure App Service.

### Using this Workflow within your java app

1. Spin up a web app in Azure App Service
1. Download publishing profile and copy XML to your clipboard
1. Create a secret named `AZURE_WEBAPP_PUBLISH_PROFILE` in your GitHub repo (Settings > Secrets > Create new), and paste XML as the value
1. Open YAML file in this repo and copy contents to your clipboard
1. Create a new Workflow in your repo, and paste the YAML content
1. Replace line 15 `<Your App Name>` with the name of your Azure Web App from step #1
1. Commit workflow

