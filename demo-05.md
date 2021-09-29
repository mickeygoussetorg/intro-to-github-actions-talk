# Demo 05 - Real World Demo Instructions

I provide some high level instructions on how to run this demo.

Estimated Demo Time: X Minutes

**Step 1: Create a Pull Request**
- open the **mywebapp/Views/Shared/_Layout.cshtml** file
- Modify the third menu option to say something like **This Conference Rocks**
- Commit the change to a branch, and create a pull request
- Notice the check that appears on the pull request, and that a workflow has started
- open **demo-05-pr.yml** workflow file and explain it
- workflow will fail, as designed

**Step 2: Create a branch protection rule**
- Open repo settings
- Create a branch protection rule that requires the build-test-branch job to pass
- Save branch protection rule settings
- Open **demo-05-pr.yml** and comment out the failing steps
- Commit to same branch, which will trigger the pull request to re-run checks
- Notice this time that the check is required
- After the workflow finishes, review output files

**Step 3: Push to Main**
- Merge the pull request to main
- Open **demo-05-push-to-main.yml** and explain what is happening
- Open repository settings, and show Environments
- Open running workflow and see visualization
- Open Slack, and show slack integration and notifications
- Show how new code is deployed to DEV and QA, but not PROD, but pulling up the websites
- Approve the push to prod
- Show the code was pushed to PROD