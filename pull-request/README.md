# Pull Request (PR)

Pull request also know as PR helps prevent code errors before merging to main branch.

## Steps to create a PR

1. Clone the repository to your local (for example I am taking my repository.)

```bash
git clone git@github.com:vutaplam/git-examples.git
```

2. Create a feature branch from main branch

```bash
git checkout -b feature/reason-for-change
```

2. Modify your code

3. Commit the changes and push

```bash
git add . 
git commit -m "This is the PR demo - usually we give our ticket number and reason for this change"
git push origin feature/reason-for-change
```

4. From <https://github.com> navigate to your repository and click on pull request tab
