# Task-1 14/10/2024

## 1. Create Simple Hello World .Net Application
- Create an API that returns "Hello World!"

## 2. Create GitHub Actions for the Repository
- **Action 1:**
  - When a user commits changes to a feature branch and raises a merge request to the master branch, it should trigger an email to the approver for approval. Once approved, it should merge the changes to the master branch.
- **Action 2:**
  - Once changes are merged to the master branch, it should trigger another GitHub Workflow for building the application, generating a release, and uploading it to Octopus Deploy.

## 3. CI Workflow
The CI Workflow should contain the following stages:
1. Checkout
2. Setup environment
3. Build project
4. Scan it using Checkmarx
5. Publish/Upload artifact to Octopus Deploy

## 4. Create Simple Octopus Deploy Process
Create a process to use the release and deploy it to the Development environment with the following steps:
1. Raise Approval request
2. Setup Environment
3. Deploy Application to local machine
