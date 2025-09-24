## Step 1: Create and Prime Your Copilot Space

In this step you will establish a Copilot Space and give it the minimum context it needs to act as a project management knowledge hub for OctoAcme.

### What you will do now

1. Create a new Copilot Space (this is the container for all subsequent conversations).
2. Add high‑level Instructions (purpose, where process docs live, why the Space exists).
3. Attach (add as a Source) your cloned exercise repository so Copilot can index `docs/` and issue templates.
4. Confirm the repository finishes indexing (appears in Sources).
5. Start a conversation in the Space to generate an issue that will track creating a README summarizing OctoAcme project management processes and linking every document in `docs/`.

### Copilot usage requirements (apply to every conversation here)

- Model: GPT-4.1
- For pull request draft generation: include the phrase `Using the github-copilot-agent tool` in your prompt (PR drafts use the GHCP coding agent).
- Keep prompts explicit about desired outputs (issues, summaries, links).

### Readiness checklist before proceeding

- You can access https://github.com/copilot/spaces
- You have (or will fork) the exercise repository
- You know your GitHub username to build the repository URL
- You can wait for indexing (a few seconds to a few minutes)

Proceed to the activities below to execute each action.

[Use Copilot Spaces](https://docs.github.com/en/copilot/how-tos/provide-context/use-copilot-spaces/)

> [!IMPORTANT]
> In all conversations with Copilot Spaces, always be aware of the following:
> Use the GPT-4.1 model
> Pull request drafts utilizes GHCP coding agent, therefore your prompt should contain `Using the github-copilot-agent tool`

### ⌨️ Activity: Create your OctoAcme Project Management Hub Copilot Space

1. Navigate to GitHub Copilot Spaces https://github.com/copilot/spaces (ensure you have access to this feature)
1. Click "Create new Space" or the equivalent option
1. Name your Space: ex. "OctoAcme Project Management Hub"
1. Add a description: "Centralizing and democratizing project management knowledge for the OctoAcme organization"
1. Create the Space

<! image place holder>

### ⌨️ Activity: Add instructions to your Copilot Space

- In your newly created Copilot Space, look for "Instructions" section
- Add the following instructions to provide context about the repository and its purpose:

   > ```markdown
   > ## Program process documents
   >
   > - Stored in `docs/`
   >
   > ### Purpose of this Copilot Space
   >
   > - Centralize scattered project management knowledge in Copilot Spaces
   > - Convert tacit tribal insights into searchable, versioned artifacts
   > - Give all team members equal access to processes, decisions, and rationale
   > - Connect a repository as a structured knowledge source
   > - Extract, refine, and standardize workflows collaboratively
   > - Feed validated improvements back into living documentation
   > - Accelerate onboarding and reduce single-person dependency risk
   > - Enable consistent, repeatable project execution
   >
   > ## Issue templates for program process documents
   >
   > - Stored in `.github/ISSUE_TEMPLATE/`
   > ```

<! image place holder >

### ⌨️ Activity: Add your cloned repository as a source repository to your Copilot Space

1. In your newly created Copilot Space, look for "Sources" or "Add Source" section
1. Add this exercise repository as a source:
   - Repository URL: `https://github.com/<your-username>/<repo-name>`  
     (Replace `<your-username>` with your GitHub username and `<repo-name>` with the name of your fork or copy of this repository. For example: `https://github.com/octocat/skills-democratize-tribal-knowledge-using-copilot-spaces`)
   - This gives Copilot access to the project management documentation and processes
1. Wait for the repository to be indexed (this may take a few seconds to a few minutes depending on size)
1. Verify the repository appears in your sources list

### ⌨️ Activity: Create an issue in the repository for a README for OctoAcme Project Management Docs

> [!IMPORTANT]
> Use the GPT-4.1 model for all conversations with Copilot Spaces.

- Open your Copilot Space you created above. https://github.com/copilot/spaces
- In the conversation interface prompt the following:

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > Create an issue in the repository for a README for OctoAcme Project Management Docs that has links to all the docs in the docs folder.
   > - The README should also contain a brief summary of the project management processes used by OctoAcme.
   > - Make sure README and project management processes summary and links are in the title of the issue.
   > ```

You can then add this issue by hitting the "Create Issue" button.

<! image place holder >

<details>
<summary>Having trouble? 🤷</summary><br/>

- Make sure you have access to GitHub Copilot Spaces (currently in beta/limited access)
- The repository should be publicly accessible for Copilot to index it
- If you can't access Copilot Spaces, you can continue by manually exploring the repository structure and documentation
- Repository indexing can take 5-10 minutes depending on size

</details>
