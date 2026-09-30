# Salesforce Student Enrollment App

Salesforce DX source folder for the Student Enrollment project.

## Included
- Instructor custom object
- Instructor Code field
- Expertise picklist
- Phone field
- Email field

## VS Code
1. Open this folder in VS Code.
2. Install Salesforce Extension Pack.
3. Authorize your Salesforce org.
4. Deploy the source from `force-app/main/default`.

## Deploy with Salesforce CLI
```bash
sf project deploy start --source-dir force-app/main/default
```

## GitHub
After opening this folder in VS Code:
```bash
git init
git add .
git commit -m "Add Salesforce Student Enrollment source"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```
