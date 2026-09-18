# Checkpoint 2 — Feature Branch & Pull Request Workflow

## Goal

Show that you can complete the core Git development workflow safely without working directly on `main`.

```text
clone
→ create feature branch
→ edit
→ git status
→ git add
→ git commit
→ git push
→ open Pull Request
```

CP4 later tests the mental model behind local/remote repositories. CP2 is about performing the workflow correctly.

## Start the exercise

[![Copy Exercise](https://img.shields.io/badge/COPY%20EXERCISE-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=KLIS-CS&template_name=GitHub-Feature-Branch-Pull-Request-Workflow&owner=%40me&name=cp2-feature-branch-pr-workflow&description=Checkpoint+2:+Feature+Branch+%26+Pull+Request+Workflow&visibility=public)

Keep the copied repository **Public**. The mother repository needs public read access so your automatic score and teacher grade can be synchronized.

After the copy is created:

1. Open **Actions**.
2. Select **Start Exercise**.
3. Choose **Run workflow**.
4. Read the Exercise Issue GitHub Actions creates.
5. Clone your copied repository to your computer.
6. Complete the checkpoint locally.

## Required branch

```text
cp2-YOUR-GITHUB-USERNAME
```

Do **not** work directly on `main`.

## Challenge

On your required CP2 branch:

1. Open `feature.txt` and replace the starter line with a short feature description.
2. Complete `submission.md`.
3. Use `git status` before and after staging.
4. Stage your work with `git add`.
5. Commit with a meaningful message.
6. Push the required branch to GitHub.
7. Open a Pull Request from your CP2 branch into `main`.
8. Leave the Pull Request **open** for grading.

Your Pull Request should change only:

```text
feature.txt
submission.md
```

The grader checks that `main` still contains the untouched starter file.

## Automatic grading — 60 points

| Evidence | Points |
|---|---:|
| Correct `cp2-USERNAME` branch exists | 10 |
| `main` still has the untouched starter file | 10 |
| `feature.txt` changed on the CP2 branch | 10 |
| CP2 branch has at least one commit ahead of `main` | 10 |
| Open Pull Request from CP2 branch → `main` | 10 |
| PR changes only the allowed files | 5 |
| `submission.md` is complete | 5 |
| **Automatic total** | **60** |

Your copied repository runs the automatic grader and creates/updates a **CP2 — Score** Issue. Detailed automatic evidence remains linked to the CP2 progress output.

## Submit for teacher grading

When the automatic evidence is ready, submit the copied repository to the mother repository:

[![Submit CP2](https://img.shields.io/badge/SUBMIT%20CP2-%E2%86%92-0969da?style=for-the-badge&logo=github)](https://github.com/KLIS-CS/GitHub-Feature-Branch-Pull-Request-Workflow/issues/new?template=cp2-submission.yml)

The teacher grades from the **KLIS-CS mother repository**, not from the student's PR.

Teacher rubric:

- Branch safety — 10
- Git workflow explanation — 10
- Pull Request understanding — 10
- Reflection & work quality — 10

After the teacher enters `/manual-grade` in the mother repository, the `/40` teacher score is published and pulled back into the student's own **CP2 — Score** Issue.

```text
Student repository
→ automatic /60
→ Submit CP2
→ mother repository /manual-grade /40
→ teacher grade published
→ student's CP2 — Score updates
→ Final score /100
```

The student score sync checks automatically about once per hour. It can also be refreshed with:

**Actions → CP2 — Student Score → Run workflow**

## Checkpoint Navigation

| Checkpoint | Skill | Link |
|---|---|---|
| CP1 | Repository Setup | [Open](https://github.com/KLIS-CS/GitHub-Repository-Setup) |
| **CP2 — You are here** | Feature Branch & Pull Request | [Open](https://github.com/KLIS-CS/GitHub-Feature-Branch-Pull-Request-Workflow) |
| CP3 | Issues & Projects | [Open](https://github.com/KLIS-CS/GitHub-Issues-Projects-Workflow) |
| CP4 | Local ↔ Remote | [Open](https://github.com/KLIS-CS/KLIS-CS-Git-Local-Remote-Workflow) |
| CP5 | Final Integrated Challenge | [Open](https://github.com/KLIS-CS/GitHub-Final-Integrated-Challenge) |

[Back to GitHub Foundations Hub](https://github.com/KLIS-CS/GitHub-Foundations)
