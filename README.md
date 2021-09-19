# Intro To GitHub Actions Presentation

I contain the demos related to my Intro to GitHub Actions Presentation.






## Workflows

### demo-01.yml (Demo 01 - Basic Workflow)

I am used to explain the basic workflow structure.

### demo-02.yml (Demo 02 - Matrix Builds)

I am used to explain how to execute a matrix build.

### demo-03.yml (Demo 03 - Jobs and Chaining)

I am used to explain how to chain multiple jobs together.

### demo-04.yml (Demo 04 - Context Variables)

I am used to explain context variables.

### demo-05-pr.yml (Demo 05 - Pull Request)

I am used to show triggering on a pull request, and branch protection rules.

### demo-05-push-to-main.yml (Demo 05 - Push To Main)

I am used to show triggering on a push to main.

- Create a change to README. The PR workflow should trigger and pass
- Modify the PR workflow to fail. Notice how the PR can still be merged
- Create a branch protection rule for the main branch that requires that PR
- Modify Readme, and see how PR now can't be merged (unless you are an admin)
- Remove the branch protection rule, and remove the fail step.  PR should be able to merge
- Merge and watch the push workflow run

### demo-06-pr.yml (Demo 06 - Pull Request)

I am used to show triggering on a pull request that builds the web app

### demo-06-push-to-main.yml (Demo 06 - Push To Main)

I am used to show triggering on a push to main, using environments, and deploying to Azure.
