Steps performed to create and configure repository 'custom-mcp-server-built-on-Spring-AI':

1. Created a new public GitHub repository named 'custom-mcp-server-built-on-Spring-AI' under user tridib23021983.
2. Initialized repository with basic files: README.md, .gitignore, LICENSE.
3. Added a simple test Java file at src/test/java/ExampleTest.java to verify project structure.
4. Default branch set to 'main'.
5. Ensure branch protection and other settings can be configured locally by the owner after cloning if required.

Commands used (locally) - example to clone and push changes:

# Clone the repo
$ git clone git@github.com:tridib23021983/custom-mcp-server-built-on-Spring-AI.git
$ cd custom-mcp-server-built-on-Spring-AI

# Create a new feature branch locally
$ git checkout -b feature/my-change

# Make changes, commit and push
$ git add .
$ git commit -m "My change"
$ git push -u origin feature/my-change

# Create a pull request on GitHub to merge feature branch into main

Notes:
- Repository is public. If you want private, change settings on GitHub or request me to update.
- Branch protection rules, required status checks, CODEOWNERS, and CI configuration were not set automatically. Recommend enabling CI (GitHub Actions), branch protection, and required reviews for production workflows.
