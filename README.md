# acm-github-workshop

Practice GitHub collaboration by adding your ACM member profile.

Welcome to the ACM @ UCF Git + GitHub workshop! We’re building a shared member directory, one profile at a time.

**Your goal:** add your profile in your own fork, commit it to a branch, and open a pull request to this repository. A workshop maintainer will review and merge it.

You only need a GitHub account and a browser for this activity.

## Before you start

- Sign in to [GitHub](https://github.com/).
- Keep this original repository open in a tab so you can return to it later.
- Replace `USERNAME` in the instructions with your GitHub username.
- This repository is public. Share only information you’re comfortable making public. A first name or nickname is enough, and every profile field is optional.

## 1. Fork this repository

1. Click **Fork** near the top right of this repository.
2. Set **Owner** to your personal GitHub account.
3. Keep the repository name and click **Create fork**.

**Checkpoint:** the repository owner at the top of the new page should be your username. You should also see **forked from** the original repository.

You’ll make your changes in this fork. You don’t need write access to the original repository.

## 2. Create your branch

1. In your fork, open the **Code** tab.
2. Click the branch dropdown above the files. It should currently say **main**.
3. Type `add-USERNAME-profile`, replacing `USERNAME` with your GitHub username.
4. Click **Create branch** to create it from `main`.

For example, if your username is `alex123`, your branch is `add-alex123-profile`.

**Check:** your new branch should now appear in the branch dropdown.

## 3. Add your profile

1. From the main file list in your fork, select **Add file**, then **Create new file**.
2. Enter this filename, replacing `USERNAME` with your GitHub username:

   ```text
   members/USERNAME.md
   ```

   Typing `/` creates or enters the folder. If you’re already inside `members`, enter only `USERNAME.md`.

3. Paste this template into the editor:

   ```markdown
   # [First name or nickname]

   - Major: [Your major]
   - Interests: [Your interests]
   - I want to build: [Your project idea]
   - Fun fact: [Optional]
   ```

4. Replace the bracketed text with your own information. Delete any lines you don’t want to share.
5. Use **Preview** to check the formatting.

Create your own file. Leave this README and other members’ profiles unchanged.

## 4. Commit your change

1. Click **Commit changes…** above the editor.
2. Enter a short message, such as `Add my member profile`.
3. Commit directly to your current `add-USERNAME-profile` branch.
4. Click the final **Commit changes** button.

**Checkpoint:** your profile file and new commit should now be visible on your profile branch.

Because you committed through the website, your commit already lives on GitHub. There’s no separate push step in this activity.

## 5. Open your pull request

1. Return to the **original workshop repository** using the tab you kept open.
2. Open **Pull requests**, then click **New pull request**.
3. Click **compare across forks** if the repository selectors are hidden.
4. Check these selections:

   | Selection | What to choose |
   | --- | --- |
   | Base repository | The original workshop repository |
   | Base branch | `main` |
   | Head repository / head fork | Your fork |
   | Compare branch | Your `add-USERNAME-profile` branch |

5. Read the changes. You should see one new file: `members/USERNAME.md`.
6. Click **Create pull request** to open the form.
7. Give it a title such as `Add my member profile` and a short description of your contribution.
8. Click the final **Create pull request** button.

**Checkpoint:** your pull request should be open in the original repository. Raise your hand when you reach this point!

## You’re done!

An **open pull request** is the finish line for this activity. A maintainer will review it and merge it when it’s ready. Opening the PR does not automatically change `main`.

Finished early? Read a classmate’s pull request and leave a friendly, useful comment.

If a maintainer asks you to change something, edit your profile on the same branch and commit again. That commit will appear in your existing PR.

## Stuck?

| Problem | What to check |
| --- | --- |
| I can’t edit or create a file | Check that you’re signed in and working in your own fork. |
| I’m on the wrong branch | Select `add-USERNAME-profile` before editing or comparing. |
| The comparison shows no changes | Check that you committed the file and selected your profile branch as the compare branch. |
| My PR is going to my fork | Set the base repository to the original workshop repository and the base branch to `main`. |
| My filename already exists | Ask a helper before changing or replacing an existing profile. |

Ask a workshop helper whenever you need a hand.

## Keep practicing

- [GitHub Hello World tutorial](https://docs.github.com/en/get-started/using-github/hello-world)
- [Fork a repository](https://docs.github.com/en/pull-requests/how-tos/work-with-forks/fork-a-repo)
- [Create a new file on GitHub](https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files)
- [Create a pull request from a fork](https://docs.github.com/en/pull-requests/how-tos/create-pull-requests/creating-a-pull-request-from-a-fork)
- [Official Git command cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)
