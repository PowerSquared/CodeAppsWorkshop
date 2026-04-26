# Module 05 — Governance, ALM & Deployment

In this module you will deploy your finished app to Power Platform and learn how Code Apps fit into a governed, production-ready ALM process.

## Prompts

### 1. Deploy the app

```
Deploy the app to Power Platform
```

Verify the deployed app opens correctly in the browser and that the Dataverse data loads as expected.

### 2. Set up source control

```
Set up a Git repository for this project and create an initial commit with all the app files
```

### 3. Plan your ALM strategy

```
Based on this Code App project, write up a recommended ALM strategy covering: branching, environment promotion (dev → test → prod), and how to handle Dataverse schema changes across environments
```

Review the output with the group — this is a discussion point, not something to implement fully today.

## Key concepts covered

- **Environments** — dev, test, and production environments in Power Platform
- **Solution layers** — how Code Apps and Dataverse tables sit inside solutions
- **Pipelines** — using Power Platform Pipelines or Azure DevOps to promote between environments
- **DLP policies** — how Data Loss Prevention policies affect connector usage in Code Apps
- **Managed vs unmanaged solutions** — why you deploy managed solutions to production
