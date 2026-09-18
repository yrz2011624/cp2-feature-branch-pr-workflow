# Checkpoint 2 Submission

Name:Tom
GitHub Username:yrz2011624
Required Branch:cp2-yrz2011624
Pull Request Number:3

## Commands Used

Write the commands you used, one per line, in the order you used them.
git clone https://github.com/yrz2011624/cp2-feature-branch-pr-workflow.git . 
git branch cp2-yrz2011624
git switch cp2-yrz2011624
git status
git add.
git push origin -u cp2-yrz2011624
```text

```

## Question 1 — Branch Safety

Why should you avoid doing this checkpoint directly on `main`?

Answer:直接在main分支上修改会导致错误，并且不能回退

## Question 2 — Stage vs Commit

What is the difference between `git add` and `git commit`?

Answer:git add is used to stage changes from your working directory into the staging area (also called the index). This tells Git exactly which file versions you want to include in your next commit. If you modify a file after running git add, you must run it again to stage the latest version.git commit takes the staged changes and records them in the local repository as a new commit with a unique hash. This commit is a snapshot of the project at that moment. You can add a message describing the changes using -m.

## Question 3 — Commit vs Push vs Pull Request

Explain what changes when you commit locally, when you push the branch, and when you open a Pull Request.

Answer:commit locally：本地保存push the branch：其他分支保存open a Pull Request：main分支保存

## Reflection

What Git command or checkpoint helped you understand the repository state most clearly, and why?

Answer:git status, It lets you see which changes have been staged, which haven’t, and which files aren’t being tracked by Git.
