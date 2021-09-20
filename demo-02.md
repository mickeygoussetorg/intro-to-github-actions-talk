# Demo 02 - Matrix Strategies Demo Instructions

I provide some high level instructions on how to run this demo.

Estimated Demo Time: X Minutes

- Open the mickeygoussetorg/intro-to-github-actions-talk repo
- Show the .github/workflows folder, and mention how all workflows have to go in that folder
- Open demo-02.yml in web browser
- Walk through file and explain what is happening
  - Strategy | Matrix
  - runs-on
- Click the Actions Tab
- Click Demo 02
- Run the workflow against the main branch
- Click into the workflow run
- Explain the main page
  - We should see three jobs execute
- View Results
- Open demo-02.yml in web browser
- Click pencil to edit
- Uncomment Python in Matrix and Python in Step
- Ask audience how many times they think this will run
- Push it to main
- Run Demo 02 again
- View workflow run and see how many jobs are started
- Mention that with hosted runners you can have 20 concurrent jobs at once
- Notice how all the jobs run at the same time.