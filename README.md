# Task Assignment

## 1. Create a Simple "Hello World" .NET Application
- Develop an API that responds with the message "Hello World!".

## 2. Implement GitHub Actions for the Repository

### Action 1:
- Create a GitHub Workflow that automatically builds the application, generates the package, and uploads the artifact to Octopus Deploy.

### Action 2:
- Establish a workflow where, upon committing changes to a feature branch and raising a pull request (merge request) to the master branch, an approver is automatically assigned based on predefined criteria. Once approved, the workflow should automatically merge the changes into the master branch.

## 3. Continuous Integration (CI) Workflow
The CI Workflow should include the following stages:
1. **Checkout**: Retrieve the latest code from the repository.
2. **Setup Environment**: Configure the environment required for building and deploying the project.
3. **Build Project**: Compile and build the .NET application.
4. **Publish/Upload Artifact to Octopus Deploy**: Publish the built application and upload the release artifact to Octopus Deploy for deployment.

