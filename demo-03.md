# Demo 03 - Jobs and Chaining Demo Instructions

I provide some high level instructions on how to run this demo.

Estimated Demo Time: X Minutes

- Open the mickeygoussetorg/intro-to-github-actions-talk repo
- Show the .github/workflows folder
- Open demo-03.yml in web browser
- Walk through file and explain what is happening
  - We have four jobs that when we run this should all run in parallel
- Click the Actions Tab
- Click Demo 03
- Run the workflow against the main branch
- Click into the workflow run
- Explain the main page
  - We should see four jobs execute in parallel
- View Results
- Open demo-03.yml in web browser
- Click pencil to edit
- Uncomment All the needs statements
  - Explain we are starting with Job 1, fanning out to Job 2 and 3, fanning back in to Job 4
- Push it to main
- Run Demo 03 again
- View workflow run and see jobs run. Explain visualization
