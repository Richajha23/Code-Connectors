# CodeConnectors
👋 Hello, I'm Richa Jha
This is my first Git Repository.

Skills Flowchart

```mermaid
graph TD;
    A[Skills] --> B[Languages]
    A --> C[Concepts]
    A --> D[Tools]
    B --> E[HTML]
    B --> F[C]
    B --> G[C++]
    C --> H[Data Structures]
    C --> I[Algorithms]
    D --> J[Git]
    D --> K[GitHub]
    D --> L[VS Code]
#!/bin/bash

# Initialize a new Git repository
git init my-repo
cd my-repo

# Create and switch to a new branch
git checkout -b new-branch

# Make some changes and commit them
echo "Some changes" > file.txt
git add file.txt
git commit -m "Add some changes"

# Switch back to the main branch
git checkout main

# Merge the new branch into the main branch
git merge new-branch

# Display the Git log to verify the merge
git log --oneline --graph



