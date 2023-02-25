# Commit and Push to Protected Branch
A Github Action that is able to push the pending changes of a codebase on a branch protected by pull request.

## Usage
Add the following step to your workflow

```yaml
- name: Commit and Push to Protected Branch
  uses: fabriziocacicia/commit-and-push-to-protected-branch-action@v0.1.0
  with:
    commit_message: "commit message"
```

### Action inputs

| Name | Description | Default | Required |
| --- | --- | --- | --- |
| git_user_name | The name of the git user of the commit |Commit and Push to Protected Branch Action | false |
| git_user_email | The email of the git user of the commit | <> | false |
| temp_branch | The name of the temporary branch | temp | false |
| commit_message | The message of the commit that will hold the changes |  | true |
