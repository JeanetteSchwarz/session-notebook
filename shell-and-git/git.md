# Basic Workflow for a pull request

- Create a new branch with git switch -c <branchname>.
- Make changes to the code / write your code fpr the feature.
- Push the changes and the new branch with git push -u origin <branchname> (after you have done this once you can use git push for this branch)
- Create a pull request on GitHub from the new branch into main
- Share the pull request with your team
- Review the pull request, implement changes if needed, push again to update the pull request until it gets approved
- Merge the pull request into main
- Don't forget to git pull inside the main branch on your local machine
- Delete the new branch on GitHub and locally

## 💡 This workflow is very fundamental to web developers in all of the industry. We will continue to work in this way, especially in the capstone project. So try to get comfortable with each step, it will become second nature very quickly.

### Problems deleting the branch

Message: Your configuration specifies to merge with the ref 'refs/heads/notes/github-and-markdown'
from the remote, but no such ref was fetched.
