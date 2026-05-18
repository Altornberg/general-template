## New repo? Look here!

If you have just made a new repo using this template, here are some things you might need to know:

- Fill in the readme with accurate instructions for your project.
- If applicable, add your used dependencies to the [Requirements](./requirements.txt) file.
- Pick a license. [LICENSE](./LICENSE) currently has a placeholder with a few suggestions.
- [Release Workflow](./.github/workflows/release.yml)
    - You should adjust the `APP_FILES` variable in the workflow to include files you want in the release.
    - Add any language-specific build/test steps.
- [CI Workflow](./.github/workflows/ci.yml)
    - Adjust the CI (continuous integration) workflow if needed.
- Review [.gitignore](./.gitignore) and add any project-specific patterns.
- The issue templates and PR template in .github/ can be customized, added to, or removed as needed.
- Set up branch protection for `main` in Settings → Branches (require PR + CI to pass before merging, restrict force pushes and deletions).
- Enable auto-delete of head branches in Settings → General (keeps the repo clean after merges).

### Optional GitHub features worth looking into
These are not required but may be useful depending on your project:
- **Dependabot** — alerts you when a dependency has a known vulnerability, and can optionally open a PR with the fix automatically (Security tab)
- **Copilot code review** — AI-assisted PR reviews (Settings → Copilot)
- **Merge strategy** — squash, merge commit, or rebase (Settings → General)
- **CODEOWNERS** — auto-assign reviewers based on file paths (`.github/CODEOWNERS`)


*Remove everything up to and including this line once you are comfortable with the above steps, this section is just for the template and setup.*
# Project Name

Short description of what this project does and who it's for.

---

## For users

### Requirements
- ...

### Installation
1. Download the latest release from the [Releases page](../../releases)
2. Unzip and navigate to the folder
3. Install dependencies: ...
4. Run: ...

---

## For developers

### Setup

1. Clone the repo and navigate into it
2. Set up...
3. Install dependencies...

### Running tests
```bash
add test command here
```

### Releasing
Push a v* tag to trigger the release workflow:
```bash
git tag vX.Y.Z
git push origin vX.Y.Z
```
